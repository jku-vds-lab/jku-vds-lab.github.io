---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Comparative Evaluations of Visualization Onboarding Methods" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Comprehending and exploring large and complex data is becoming increasingly important for users in a wide range of application domains. Still, non-experts in visual data analysis often have problems with correctly reading and interpreting information from visualizations that are new to them. To support novices in learning how to use new digital technologies, the concept of onboarding has been successfully applied in other fields and first approaches also exist in the visualization domain. However, empirical evidence on the effectiveness of such approaches is scarce. Therefore, we conducted 3 studies: 1) Firstly, we explored the effect of vis onboarding, using an interactive step-by-step guide, on user performance for four increasingly complex visualization techniques. We performed a between-subject experiment with 596 participants in total. The results showed that there are no significant differences between the answer correctness of the questions with and without onboarding. Furthermore, participants commented that for highly familiar visualization types no onboarding is needed. 2) Second, we performed another study with MTurk workers to assess if there is a difference in user performances on different onboarding types: step-by-step, scrollytelling tutorial, and video tutorial. The study revealed that the video tutorial was ranked as the most positive on average, based on sentiment analysis, followed by the scrollytelling tutorial and the interactive step-by-step guide. 3) For our third study with students, we gathered data on users' experience in using an in-situ scrollytelling for the VA tool. The results showed that they preferred scrollytelling over the tutorial integrated into the landing page. In summary, the in-situ scrollytelling approach works well for visualization onboarding and a video tutorial can help to introduce interaction techniques." 

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
shortname: CompareEvaluations
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2022_arxiv_compare_evaluations.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2022_arxiv_compare_evaluations_teaser.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Christina Stoiber
- walchshofer
- Margit Pohl
- Benjamin Potzmann
- Florian Grassinger
- stitz
- streit
- Wolfgang Aigner

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: Visual Informatics
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2022

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Visual Informatics		# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle:
  editor:
  publisher: Elsevier
  doi: 10.1016/j.visinf.2022.07.001 # e.g.10.1109/TVCG.2020.3012063
  url: https://doi.org/10.1016/j.visinf.2022.07.001
  volume: 
  number: 
  pages: 
  month: March

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
pdf: 2022_visinf_compare_evaluations_onboarding.pdf
# A supplement PDF e.g. 2017_preprint_taggle_supplement.pdf; this is usually uploaded to the caleydo aws server
supplement: 

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Preprint (arxiv)
  abslink: https://arxiv.org/abs/2203.15418
  linksym: true
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

The authors wish to thank Victor Adriel de Jesus Oliveira for his valuable feedback. This work was funded by the Austrian Ministry for Transport, Innovation and Technology (BMVIT) under the ICT of the Future program via the SEVA project (no. 874018), as well as the FFG, Contract No. 881844: "Pro2Future is funded within the Austrian COMET Program Competence Centers for Excellent Technologies under the auspices of the Austrian Federal Ministry for Climate Action, Environment, Energy, Mobility, Innovation and Technology, the Austrian Federal Ministry for Digital and Economic Affairs and of the Provinces of Upper Austria and Styria. COMET is managed by the Austrian Research Promotion Agency FFG."
