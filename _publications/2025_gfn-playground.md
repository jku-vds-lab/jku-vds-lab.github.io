---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "GFlowNet Playground - Theory and Examples for an Intuitive Understanding" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: preprint
abstract: "Imagine you want to discover new molecules for a life-saving drug. With an estimated size of 10^60, the space of possible molecular structures is vast, and promising candidates are potentially sparse and difficult to find. Traditional methods might guide you to a single best guess, but what if this guess is toxic, has side effects, or fails in a later stage of testing? What if you need many diverse, high-quality candidates to test? This is where Generative Flow Networks (GFlowNets) come in. They are a class of generative models that don't just aim for a single optimal solution—they aim to diversely sample from a space of possibilities, with a preference for high-reward outcomes.
In this article, we introduce the core concepts behind GFlowNets, outline their theoretical foundations and common training pitfalls, and guide readers toward an intuitive understanding of how they work. We provide an interactive Playground, where reward functions and hyperparameters can be adjusted on the fly to reveal a GFlowNet’s learning dynamics. A Tetris example brings these ideas to life, as the network uncovers stacking strategies in real time. By journey’s end, readers will have both a practical grasp of GFlowNet behavior and inspiration for applying them to their own challenges." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://jku-vds-lab.at/
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: GFlowNet Playground
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2025_gfn-playground_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2025_gfn-playground.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Florian Holeczek
- Alexander Hillisch
- hinterreiter
- Alex Hernández-García
- streit
- humer

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: VISxAI
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2025

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://visxai.io/ # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: 8th Workshop on Visualization for AI Explainability 		# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 		# e.g.10.1109/TVCG.2020.3012063
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
external-project: https://gfn-playground.jku-vds-lab.at/

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
# code: https://github.com/jku-vds-lab/hoxai-at-visxai

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements
The work was partyly funded by the Austrian Science Fund under grant number FWF DFH 23–N,
Some implementations and ideas are based on great work of others:
The continuous line example by Joseph Viviano & Kolya Malkin. The idea for the playground environment is based on their notebook and much of the training code is adapted from their tutorial. The neural network playground by Daniel Smilkov and Shan Carter was an inspiration on how to visualize machine learning and the training progress in the browser. The code for the flow field visualization is adapted from Mathcurious' implementation.