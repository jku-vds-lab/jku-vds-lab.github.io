---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Transitioning to a Commercial Dashboarding System: Socio-technical Observations and Opportunities" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Many long-established, traditional manufacturing businesses are becoming more digital and data-driven to improve their production. These companies are embracing visual analytics in these transitions through their adoption of commercial dashboarding systems. Although a number of studies have looked at the technical challenges of adopting these systems, very few have focused on the socio-technical issues that arise. In this paper, we report on the results of an interview study with 17 participants working in a range of roles at a long-established, traditional manufacturing company as they adopted Microsoft Power BI. The results highlight a number of socio-technical challenges the employees faced, including difficulties in training, using and creating dashboards, and transitioning to a modern digital company. Based on these results, we propose a number of opportunities for both companies and visualization researchers to improve these difficult transitions, as well as opportunities for rethinking how we design dashboarding systems for real-world use." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
# paper_content_url:
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: Barriers
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2023_barriers_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2023_barriers.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- walchshofer
- dhanoa
- streit
- Miriah Meyer

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: IEEE Vis
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
# publisherurl: # add link to publisher page of your publication

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics	# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle: 
  editor: 
  publisher: IEEE Computer Society
  address: 
  doi: 10.1109/TVCG.2023.3326525		# e.g.10.1109/TVCG.2020.3012063
  url: 
  volume: 30
  number: 01
  pages: 381-391
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
pdf: 2023_barriers.pdf
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
We would like to thank Jimmy Moore for the input-rich discussions at the beginning of the project, our interviewees for their time and candid participation in the study, and our reviewers for their feedback. This work was supported in part by funding from the Wallenberg AI, Autonomous Systems and Software Program (WASP) funded by the Knut and Alice Wallenberg Foundation, the Austrian Science Fund (FWF DFH 23--N), and the Austrian Research Promotion Agency (FFG 881844). Pro<sup>2</sup>Future is funded within the Austrian COMET Program under the auspices of the Austrian Federal Ministry for Climate Action, Environment, Energy, Mobility, Innovation and Technology, the Austrian Federal Ministry for Digital and Economic Affairs, and of the States of Upper Austria and Styria. COMET is managed by the Austrian Research Promotion Agency FFG.