---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Reassuring, Misleading, Debunking: Comparing Effects of XAI Methods on Human Decisions"

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "Trust calibration is essential in AI-assisted decision-making. If human users understand the rationale on which an AI model has made a prediction, they can decide whether they consider this prediction reasonable. Especially in high-risk tasks such as mushroom hunting (where a wrong decision may be fatal), it is important that users make correct choices to trust or overrule the AI. Various explainable AI (XAI) methods are currently being discussed as potentially useful for facilitating understanding and subsequently calibrating user trust. So far, however, it remains unclear which approaches are most effective. In this article, the effects of XAI methods on human AI-assisted decision-making in the high-risk task of mushroom picking were tested. For that endeavor, the effects of (i) Grad-CAM attributions, (ii) nearest-neighbor examples, and (iii) network-dissection concepts were compared in a between-subjects experiment with N=501 participants representing end-users of the system. In general, nearest-neighbor examples improved decision correctness the most. However, varying effects for different task items became apparent. All explanations seemed to be particularly effective when they revealed reasons to (i) doubt a specific AI classification when the AI was wrong and (ii) trust a specific AI classification when the AI was correct. Our results suggest that well-established methods, such as Grad-CAM attribution maps, might not be as beneficial to end users as expected and that XAI techniques for use in real-world scenarios must be chosen carefully." 

# insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


# set this url, if your paper is on another server; defaults to data.jku-vds-lab.at
paper_content_url: https://doi.org/10.31219/osf.io/h6dwz
# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "hide" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: HOXAIStudy2
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2022_preprint_hoxai_study2.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2022_preprint_hoxai_study2_teaser.PNG

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- humer
- hinterreiter
- Benedikt Leichtmann
- Martina Mara
- streit

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: TiiS
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: ACM Transactions on Interactive Intelligent Systems	# e.g. IEEE Transactions on Visualization and Computer Graphics (to appear)
  booktitle:
  editor:
  publisher:
  doi: 10.1145/3665647
  url: https://doi.org/10.1145/3665647
  volume: 14
  number: 3
  pages: 
  month: September

preprint: https://osf.io/h6dwz/ # here you can put the preprint link (arxiv.org, osf.io,...) e.g. https://arxiv.org/abs/1910.00969


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
code: https://osf.io/bq85c/

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements

This work was funded by Johannes Kepler University Linz, Linz Institute of Technology (LIT), the State of Upper Austria,
and the Federal Ministry of Education, Science and Research under grant number LIT-2019-7-SEE-117, awarded to
MM and MS, the Austrian Science Fund under grant number FWF DFH 23–N, and under the Human-Interpretable
Machine Learning project (funded by the State of Upper Austria). We thank Moritz Heckmann for helping with the
implementation of the AI Forest - The Schwammerl Hunting Gameand Stefan Eibelwimmer for the graphic design of the
game. We thank Dr. Otto Stoik, the members of the Mycological Working Group (MYAG) at the Biology Center Linz,
Austria, and the German Mycological Society (DGfM) for providing mushroom images for this study. Finally, we thank
Alfio Ventura for helping with the study setup.

