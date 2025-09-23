---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Personalized Complementarity in Human-AI Collaboration" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Uncertainty and the potential for complementarity between humans and AI have shaped a new kind of interaction, typically referred to as a collaborative relationship. In this paper, we pick up on the discussion of common issues in human-AI collaboration based on a literature review and further discuss ways to and challenges of personalized complementarity in human-AI relations. We hypothesize that a combination of reciprocal, mixed-initiative communication may support up-to-date mental models and therefore strengthen appropriate trust and reliance, ultimately leading to a higher chance of effectively exploiting existing complementarity potentials." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: 
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: 
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2024_personalized-complementarity_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Karin Breckner
- Thomas Neumayr
- streit
- Mirjam Augstein

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: MuC2024
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl:  # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Mensch und Computer 2024, International Workshop on Personalization and Recommendation 		# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: Mensch und Computer 2024 - Workshopband
  editor: 
  publisher: Gesellschaft für Informatik e.V."
  address: 
  doi: 10.18420/muc2024-mci-ws11-206
  url: 
  volume: 
  number: 
  pages: 
  month: 

preprint:	 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# state key of an internal tool. This will link to the tool site e.g. lineup (usually not needed)
project: 

# Use this if you have an external project website e.g. https://ordino.caleydoapp.org/
external-project: 

# (deprecated)
# # The key of the video .md file (in _videos subfolder)
# video: 
# # The key of the preview video .md file (in _videos subfolder)
# preview-video:

# the youtube-id of the video (DEPRECATED)
#youtube-id: 
# the youtube-id of the preview-video (DEPRECATED)
#preview-youtube-id: 

# add videos with metadata to the sidepanel of the publication
# parameters: 
# -name: name of the video (keep it short)
# -youtube-id: id of the video
# -description: short text description, can use markdown
# -extraurl: url with fa icon, use markdown syntax
# -slides: add multiple file entries, baseurl is http://data.jku-vds-lab.at/papers/

#videos:
# - name: 'Coral: A Web-based Visual Analysis Tool [...] @ ISMB BioVis 2022'
#   youtube-id: BmeaagRZWnU
#   timestamp: 0 # optional start timestamp
#   description: 'Usage and all applications of the Projection Space Explorer can be found on the dedicated [Landing Page](https://jku-vds-lab.at/pse/).'
#   extraurl: '[BioVis Program](http://biovis.net/2022/program_ismb/)'
#   slides:
#    - file: 2022_biovis_adelberger.pdf
#    - file: 2022_biovis_adelberger.pptx
#  file: filename to look for, prefix http://data.jku-vds-lab.at/papers/


# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: 2024_personalized-complementarity.pdf
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
# code: https://github.com/jku-vds-lab/hoxai-at-visxai

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements
This research has been conducted within the scope of the Human-Centered Artificial Intelligence (HCAI) project, funded by the Austrian Science Fund (FWF) [DFH 23-N].