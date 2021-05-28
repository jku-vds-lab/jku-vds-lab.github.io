---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Coral: a web-based visual analysis tool for creating and characterizing cohorts"
key: 2021_preprint_coral
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.jku-vds-lab.at
# paper_content_url: https://doi.org/10.1093/bioinformatics/btz009


# The shortname is used for auto-generated titels
shortname: Coral
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2021_preprint_coral.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2021_preprint_coral_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- adelberger
- eckelt
- Markus J. Bauer
- streit
- Christian Haslinger
- Thomas Zichner


journal-short: Preprint
year: 2021

bibentry: article
bib:
  journal: bioRxiv
  booktitle: 
  editor: 
  publisher:
  address: 
  doi: 10.1101/2021.05.26.445802
  url: 
  volume:
  number:
  pages:
  month: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# Use if this paper is linked to an internal project. This will link to the project site
#project: coral

# Use this if you have an external project website
external-project: https://coral.caleydoapp.org
preprint: https://www.biorxiv.org/content/10.1101/2021.05.26.445802v1 # here you can put all preprint links (arxiv.org, osf.io,...)

# The reference to the video entry
video: 2021_preprint_coral
# The reference to the preview video entry
#preview-video:

# the prerint
pdf: 2021_preprint_coral.pdf
# A supplement PDF
supplement: 2021_preprint_coral_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/Caleydo/Coral

abstract: "
<p>A main task in computational cancer analysis is the identification of patient subgroups (i.e., cohorts) based on metadata attributes (patient stratification) or genomic markers of response (biomarkers). Coral is a web-based cohort analysis tool that is designed to support this task: Users can interactively create and refine cohorts, which can then be compared, characterized, and inspected down to the level of single items. We visualize the evolution of cohorts and also provide intuitive access to prevalence information. Coral can be utilized to explore any type of cohort and sample set. Here, we focus on the analysis of genomic data from cancer patients and therefore included in the public version data from the AACR Project GENIE, The Cancer Genome Atlas, and the Cell Line Encyclopedia.</p>

<p>
  Coral is publicly available at <a href="https://coral.caleydoapp.org">https://coral.caleydoapp.org</a>.
  The source code is released at <a href="https://github.com/Caleydo/Coral">https://github.com/Caleydo/Coral</a>.
</p>"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


# Acknowledgements

We thank Andreas Wernitznig, Alex Lex, and the datavisyn GmbH team, in particular Holger Stitz, for their feedback and implementation support. The authors acknowledge the American Association for Cancer Research and its financial and material support in the development of the AACR Project GENIE registry, and members of the consortium for their commitment to open data. Interpretations are the responsibility of study authors.
