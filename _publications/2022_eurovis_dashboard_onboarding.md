---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "A Process Model for Dashboard Onboarding"
key: 2022_eurovis_dashboard_onboarding
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.jku-vds-lab.at
paper_content_url:

# The shortname is used for auto-generated titels
shortname: Dashboard Onboarding
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2022_eurovis_dashboard_onboarding.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2022_eurovis_dashboard_onboarding_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
  - dhanoa
  - walchshofer
  - hinterreiter
  - stitz
  - Eduard Groeller
  - streit

journal-short: EuroVis
year: 2022

bibentry: article
bib:
  journal: Computer Graphics Forum (EuroVis '22)
  booktitle:
  editor:
  publisher: John Wiley & Sons, Inc.
  address:
  doi: 10.1111/cgf.14558
  url: https://doi.org/10.1111/cgf.14558
  volume: 41
  number: 3
  pages: 501-513
  month: July

#preprint: https://osf.io/gux9w # here you can put all preprint links (arxiv.org, osf.io,...)

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project:

# Use this if you have an external project website
external-project: https://osf.io/gux9w

# The reference to the video entry
videos:

#  file: filename to look for, prefix http://data.jku-vds-lab.at/papers/
 - name: 'Talk @ EuroVis 2022'
   youtube-id: t7PVqvh0iQ4
   timestamp: 4888
   description: ''
   extraurl: '[EuroVis Program](https://conferences.eg.org/eurovis2022/program/)'
   slides:
    - file: 2022_eurovis_dhanoa.pptx
    - file: 2022_eurovis_dhanoa.pdf

# the prerint
pdf: 2022_eurovis_dashboard-onboarding.pdf
# A supplement PDF
supplement:

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Dashboard Onboarding Supplements
  abslink: https://osf.io/zsb5a/
  linksym: true
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code:

abstract: "Dashboards are used ubiquitously to gain and present insights into data by means of interactive visualizations.
To bridge the gap between non-expert dashboard users and potentially complex datasets and/or visualizations, a variety of onboarding strategies are employed, including videos, narration, and interactive tutorials. We propose a process model for dashboard onboarding which formalizes and unifies such diverse onboarding strategies. Our model introduces the onboarding loop alongside the dashboard usage loop.
Unpacking the onboarding loop reveals how each onboarding strategy combines selected building blocks of the dashboard with an onboarding narrative. Specific means are applied to this narration sequence for onboarding, which results in onboarding artifacts that are presented to the user via an interface. We concretize these concepts by showing how our process model can be used to describe a selection of real-world onboarding examples. Finally, we discuss how our model can serve as an actionable blueprint for developing new onboarding systems."
# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements

This work was supported in part by the FFG, Contract No. 881844: "Pro2Future is funded within the Austrian COMET Program Competence Centers for Excellent Technologies under the auspices of the Austrian Federal Ministry for Climate Action, Environment, Energy, Mobility, Innovation and Technology, the Austrian Federal Ministry for Digital and Economic Affairs and of the Provinces of Upper Austria and Styria. COMET is managed by the Austrian Research Promotion Agency FFG."
Additional support was granted by the State of Upper Austria and the Austrian Federal Ministry of Education, Science and Research via the LIT -- Linz Institute of Technology (LIT-2019-7-SEE-117), and by the Federal State of Upper Austria (Human-Interpretable Machine Learning).
This paper was partly written in collaboration with the VRVis Competence Center. VRVis is funded by BMVIT, BMWFW, Styria, SFG and Vienna Business Agency in the scope of COMET—Competence Centers for Excellent Technologies (854174) which is managed by FFG.
