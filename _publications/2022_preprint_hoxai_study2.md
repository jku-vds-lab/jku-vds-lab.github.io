---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Comparing Effects of Attribution-based, Example-based, and Feature-based Explanation Methods on AI-Assisted Decision-Making"

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: preprint
abstract: "Trust calibration is essential in AI-assisted decision-making tasks. If human users understand the reasons for a prediction of an AI model, they can assess whether or not the prediction is reasonable. Especially for high-risk tasks like mushroom hunting (where a wrong decision may be fatal), it is important that users trust or overrule the AI in the right situations. Various explainable AI methods are currently being discussed as potentially useful for facilitating understanding and to calibrate user trust. So far, however, it is unclear which approaches are most effective. Our work takes on this issue; in a between-subjects experiment with 𝑁 = 501 participants. Participants were tasked to classify the edibility of mushrooms depicted on images. We compare the effects of three XAI methods on human AI-assisted decision-making behavior: (i) Grad-CAM attributions; (ii) nearest neighbor examples; and (iii) an adoption of network dissection. For nearest neighbor examples, we found a statistically significant improvement in user performance compared to a condition without explanations. Effects did not reach statistical significance for Grad-CAM and network dissection. For the latter, however, the effect size estimators show a similar tendency as for nearest neighbor. We found that the effects also varied for different task items (i.e., mushroom images). Explanations seem to be particularly effective if they reveal possible flaws in case of wrong AI classifications or reassure users in case of correct classifications. Our results suggest that well-established methods might not be as beneficial to end users as expected and that XAI techniques must be chosen carefully in real-world scenarios." 

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
  doi: 10.31219/osf.io/h6dwz
  url: https://doi.org/10.31219/osf.io/h6dwz
  volume: 
  number: 
  pages: 
  month: October

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

