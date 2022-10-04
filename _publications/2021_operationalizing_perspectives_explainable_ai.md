---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Operationalizing Human-Centered Perspectives in Explainable AI" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "The realm of Artificial Intelligence (AI)’s impact on our lives is far reaching – with AI systems proliferating high-stakes domains such as healthcare, finance, mobility, law, etc., these systems must be able to explain their decision to diverse end-users comprehensibly. Yet the discourse of Explainable AI (XAI) has been predominantly focused on algorithm-centered approaches, suffering from gaps in meeting user needs and exacerbating issues of algorithmic opacity. To address these issues, researchers have called for human-centered approaches to XAI. There is a need to chart the domain and shape the discourse of XAI with reflective discussions from diverse stakeholders. The goal of this workshop is to examine how human-centered perspectives in XAI can be operationalized at the conceptual, methodological, and technical levels. Encouraging holistic (historical, sociological, and technical) approaches, we put an emphasis on “operationalizing”, aiming to produce actionable frameworks, transferable evaluation methods, concrete design guidelines, and articulate a coordinated research agenda for XAI." 

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
shortname: OperationalizingPerspectives
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2021_operationalizing_perspectives_explainable_ai.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2021_operationalizing_perspectives_explainable_ai_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Uphol Ehsan
- Philipp Wintersberger
- Q. Vera Liao
- Martina Mara
- streit
- Sandra Wachter
- Andreas Riener
- Mark O. Riedl

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ACM CHI
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2021

# what is the publication type and other bib specific properties
bibentry: inproceedings
bib:
  booktitle: Extended Abstracts of the 2021 CHI Conference on Human Factors in Computing Systems (CHI EA '21)
  publisher: Association for Computing Machinery, New York, NY, United States
  editor: Yoshifumi Kitamura, Aaron Quigley, Katherine Isbister, Takeo Igarashi
  doi: 10.1145/3411763.3441342
  url: https://doi.org/10.1145/3411763.3441342
  number: 94
  pages: 1--6
  month: May

#preprint: https://arxiv.org/abs/2203.15418	 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969


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

# the youtube-id of the video
youtube-id: 
# the youtube-id of the preview-video
preview-youtube-id: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: 2021_operationalizing_perspectives_explainable_ai.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: Preprint (arxiv)
#  abslink: https://arxiv.org/abs/2203.15418
#  linksym: true
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: 

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements

This work is supported under the FH-Impuls program of the German Federal Ministry of Education and Research (BMBF) under Grant Number 13FH7I01IA (SAFIR). We are grateful to members of the Human-centered AI lab at Georgia Tech for their input during brainstorming of these ideas.
