---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "ChemInformatics Model Explorer (CIME): Exploratory Analysis of Chemical Model Explanations" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "The introduction of machine learning to small molecule research – an inherently multidisciplinary field in which chemists and data scientists combine their expertise and collaborate – has been vital to making screening processes more efficient. In recent years, numerous models that predict pharmacokinetic properties or bioactivity have been published, and these are used on a daily basis by chemists to make decisions and prioritize ideas. The emerging field of explainable artificial intelligence is opening up new possibilities for understanding the reasoning that underlies a model. In small molecule research, this means relating contributions of substructures of compounds to their predicted properties, which in turn also allows the areas of the compounds that have the greatest influence on the outcome to be identified. However, there is no interactive visualization tool that facilitates such interdisciplinary collaborations towards interpretability of machine learning models for small molecules. To fill this gap, we present CIME (ChemInformatics Model Explorer), an interactive web-based system that allows users to inspect chemical data sets, visualize model explanations, compare interpretability techniques, and explore subgroups of compounds. The tool is model-agnostic and can be run on a server or a workstation." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: CIME
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2021_cime_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2021_cime_teaser.png


# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- humer
- Henry Heberle
- Floriane Montanari
- Thomas Wolf
- Florian Huber
- Ryan Henderson
- Julian Heinrich
- streit

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: J. Cheminformatics
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2022

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Journal of Cheminformatics		# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 10.1186/s13321-022-00600-z		# e.g.10.1109/TVCG.2020.3012063
  url: https://doi.org/10.1186/s13321-022-00600-z
  volume: 14
  number: 21
  pages: 
  month: 

preprint: https://doi.org/10.26434/chemrxiv-2021-crpd0 # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# state key of an internal tool. This will link to the tool site e.g. lineup (usually not needed)
project:

# Use this if you have an external project website e.g. https://ordino.caleydoapp.org/
external-project: https://cime-demo.jku-vds-lab.at/

# (deprecated)
# # The key of the video .md file (in _videos subfolder)
# video: 
# # The key of the preview video .md file (in _videos subfolder)
# preview-video:

# the youtube-id of the video
youtube-id: s9d31AZZsHo
# the youtube-id of the preview-video
preview-youtube-id: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: 2022_cheminformatics_cime.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: 2022_cheminformatics_cime_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/cime

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements
This work was supported by the JKU Visual Data Science Lab and Bayer AG (HRB 48248). We thank Michael Koch for participating in the initiation of the project and for follow-up discussions; Michael Pühringer for reading the final version of the article and Moritz Heckmann for technical support.

# Funding
This work was supported in part by Bayer AG, State of Upper Austria and the Austrian Federal Ministry of Education, Science and Research via the LIT - Linz Institute of Technology (LIT-2019-7-SEE-117), and the Austrian Science Fund (FWF DFH 23--N). 
TW and FH acknowledge funding from the Bayer AG Life Science Collaboration Project ("Machine Guided Compound Profiling"). HH, RH, FM and JH acknowledge funding from the Bayer AG Life Science Collaboration Project ("Explainable AI").
