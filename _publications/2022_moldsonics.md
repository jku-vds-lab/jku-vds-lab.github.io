---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Visualizing and Monitoring the Process of Injection Molding"

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "In injection molding machines the molds are rarely equipped with sensor systems. The availability of non-invasive ultrasound-based in-mold sensors provides better means for guiding operators of injection molding machines throughout the production process. However, existing visualizations are mostly limited to plots of temperature and pressure over time. In this work, we present the result of a design study created in collaboration with domain experts. The resulting prototypical application uses real-world data taken from live ultrasound sensor measurements for injection molding cavities captured over multiple cycles during the injection process. Our contribution includes a definition of tasks for setting up and monitoring the machines during the process, and the corresponding web-based visual analysis tool addressing these tasks. The interface consists of a multi-view display with various levels of data aggregation that is updated live for newly streamed data of ongoing injection cycles."

# insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "hide" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: moldsonics-vis
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2022_preprint_moldsonics_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2022_preprint_moldsonics_large.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- steinparz
- Thomas Mitterlehner
- Bernhard Praher
- Klaus Straka
- stitz
- streit

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: Electronic Imaging, VDA
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Electronic Imaging		# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Proceedings of the Symposium on Electronic Imaging
  editor: 
  publisher: Society for Imaging Science and Technology
  location: IS&T 7003 Kilworth Lane, Springfield, VA 22151 USA
  doi: 10.2352/EI.2023.35.1.VDA-403 # e.g.10.1109/TVCG.2020.3012063
  url: https://library.imaging.org/ei/articles/35/1/VDA-403
  volume: 35
  number: 1
  pages: 403-1--403-1

preprint: # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: "Selected for Conference Highlights Session"

# state key of an internal tool. This will link to the tool site e.g. lineup (usually not needed)
project: 

# Use this if you have an external project website e.g. https://ordino.caleydoapp.org/
external-project: http://injection-molding.jku-vds-lab.at/

# (deprecated)
# # The key of the video .md file (in _videos subfolder)
video: 
  slides:
    # - file: 2022_preprint_moldsonics_presentation.pptx
    # - file: 2022_preprint_moldsonics_presentation.pdf
# # The key of the preview video .md file (in _videos subfolder)
# preview-video:

# the youtube-id of the video
youtube-id: 
# the youtube-id of the preview-video
preview-youtube-id: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: # 2022_preprint_moldsonics.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code:

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---



