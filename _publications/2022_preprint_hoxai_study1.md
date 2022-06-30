---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Effects of Explainable Artificial Intelligence on trust and human behavior in a high-risk decision task"

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: preprint
abstract: "Understanding the recommendation of an artificially intelligent (AI) assistant for decision-making is especially important
in high-risk tasks, such as deciding whether a mushroom is edible or poisonous. To foster user understanding and appropriate trust in
such systems, we tested the effects of explainable artificial intelligence (XAI) methods and an educational intervention on AI-assisted
decision-making behavior in a 2x2 between subjects online experiment with N = 410 participants. We developed a novel use case in which
users go on a virtual mushroom hunt and are tasked with picking only edible mushrooms but leaving poisonous ones. Additionally, users
were provided with an AI-based app that shows classification results of mushroom images. For the manipulation of explainability, one
subgroup additionally received attribution-based and example-based explanations of the AI's predictions, and for the educational
intervention one subgroup received additional information on how the AI worked. We found that the group with explanations outperformed
the group without explanations and showed more appropriate trust levels. Contrary to our expectation, we did not find effects for the
educational intervention, domain-specific knowledge, or AI knowledge on performance. We discuss practical implications and introduce the
mushroom-picking task as a promising use case for XAI research." 

# insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://osf.io/n4w6u/
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "hide" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: HOXAIStudy1
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2022_preprint_hoxai_study1.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2022_preprint_hoxai_study1_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Benedikt Leichtmann
- humer
- hinterreiter
- streit
- Martina Mara

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: OSF Preprint
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2022

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: OSF Preprint		# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle:
  editor:
  publisher:
  doi: 10.31219/osf.io/n4w6u
  url: https://osf.io/n4w6u/
  volume: 
  number: 
  pages: 
  month: June

preprint: https://osf.io/n4w6u/ # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969


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
pdf:
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

# Acknowledgements

This work was funded by Johannes Kepler University Linz, Linz Institute of Technology (LIT), the State of Upper
Austria, and the Federal Ministry of Education, Science and Research under grant number LIT-2019-7-SEE-117, awarded
to MM and MS, the Austrian Science Fund under grant number FWF DFH 23–N, and under the Human-Interpretable
Machine Learning project (funded by the State of Upper Austria).
