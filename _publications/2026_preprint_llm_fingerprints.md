---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Visual Fingerprints for LLM Generation Comparison" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: preprint
abstract: "Large language model (LLM) outputs arise from complex interactions among prompts, system instructions, model parameters, and architecture. We refer to specific configurations of these factors as generation conditions, each of which can bias outputs in various ways. Understanding how different generation conditions shape model behaviors is essential for tasks such as prompt design and model evaluation, yet it remains challenging due to the stochastic and open-ended nature of text generation. We present an approach to visually compare LLM outputs across generation conditions by modeling responses as collections of linguistic choices, including content, expression, and structure. We extract these choices using natural language processing pipelines and represent their distributions across repeated samples. We then visualize these distributions as visual fingerprints, enabling direct, distribution-level comparison of condition-specific tendencies. Through four usage scenarios, we demonstrate how visual fingerprints reveal consistent patterns in LLM behavior that are difficult to observe through individual responses or aggregate metrics." 
# insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: LLM Fingerprints
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2024_preprint_llm-fingerprints-small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2024_preprint_llm-fingerprints-teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- alnouri
- hinterreiter
- humer
- Furui Cheng
- streit

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: 
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2026

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: 	arXiv Preprints	# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 		https://doi.org/10.48550/arXiv.2605.06054 # e.g.10.1109/TVCG.2020.3012063
  url: 
  volume: 
  number: 
  pages: 
  month: 

preprint: https://arxiv.org/abs/2605.06054	 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969


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
code: https://github.com/jku-vds-lab/iLLuMinate

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements

Write acknowledgements for contributors.
