# JKU Visual Data Science Lab Website
[![htmlproofer](https://github.com/jku-vds-lab/jku-vds-lab.github.io/actions/workflows/htmlproofer.yml/badge.svg?branch=htmlproofer&event=push)](https://github.com/jku-vds-lab/jku-vds-lab.github.io/actions/workflows/htmlproofer.yml)

The new Visual Data Science Lab Website built with [Jekyll](https://jekyllrb.com),
[SASS](https://www.sass-lang.com),
[Bourbon](https://bourbon.io),
[Neat](https://neat.bourbon.io),
and [Bitters](https://bitters.bourbon.io).

## Emulating github-pages

### Ruby

The site is built by Github using Jekyll.
To preview locally, use the `github-pages` gem. Briefly:

```sh
# Ruby version must be >= 2.0.0.
ruby --version
# Install bundler for dependency management:
gem install bundler
# Fetch dependencies:
bundle install
# Start server:
bundle exec jekyll serve --baseurl ""
# Get the most recent version of 'github-pages' gem:
bundle update
```

[More information](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#step-2-install-jekyll-using-bundler)

### Docker

You can use docker to build and run the site without having to install ruby and stuff. This will also watch for file changes and rebuild the site automatically.  
Page will be served at [localhost:4000](localhost:4000)

```sh
docker-compose up
```

To simply build the page, run

```sh
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll:latest jekyll build
```

## Jekyll Plugins

The only supported plugins are those that come with the [github-pages gem](https://help.github.com/articles/adding-jekyll-plugins-to-a-github-pages-site/).

## Liquid Syntax

[Liquid for Designers](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)

# Adding a Publication/Paper

You should use the template provided in [./templates/paper-template.md](./templates/paper-template.md)
for adding a new publication. Preprints will be rendered in a separate section, therefore make sure to 
update and remove it after publication (update bibtex section as well).

Each publication should be assigned an unique key like:
`YYYY_CONFSHORTNAME_PAPERSHORTNAME`

This string will be the part of the URL referencing this publication.

## Instructions for adding a new publication

1. Copy the template [./templates/paper-template.md](./templates/paper-template.md) into the folder [./_publications/<PUBLICATION_KEY>.md](./_publications/).
2. Choose a publication type, currently either **paper**, **preprint** or **thesis** and fill in the abstract
3. You should provide two images, one teaser (1200x600 ~300KB) and one thumbnail (400x200 ~70kb) to the [assets/images/papers](./assets/images/papers), you should use the key as defined above as part of the filename.
4. (optional) Upload all your videos relevant to the publication to the ICG Vis Lab YouTube Channel, and fill the template's videos section with the video's Youtube-ID
	- If you have any slides relevant to the video, upload them alongside your paper PDF as well
5. Provide all authors as a collection/list - if the author is a team member that has a separate page, provide the key instead of firstname/lastname, e.g. `streit`
6. fill in the other fields as required/available, most are optional and can be left empty
7. Upload the following files to the data AWS S3 Bucket within `'/papers'`:
    - publication as PDF (`KEY.pdf`)
    - (optional) Supplementary Material/Slides/etc. (`KEY_<CUSTOM>.<CUSTOMEXT>`)
