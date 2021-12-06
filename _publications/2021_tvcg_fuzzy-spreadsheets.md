---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Fuzzy Spreadsheet: Understanding and Exploring Uncertainties in Tabular Calculations"
key: 2021_tvcg_fuzzy-spreadsheets
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.jku-vds-lab.at
paper_content_url:

# The shortname is used for auto-generated titels
shortname: Fuzzy Spreadsheets
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2021_tvcg_fuzzy-spreadsheets.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2021_tvcg_fuzzy-spreadsheets_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
  - dhanoa
  - walchshofer
  - hinterreiter
  - Eduard Groeller
  - streit

journal-short: TVCG
year: 2021

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (Early Access)
  editor:
  publisher:
  address:
  doi: 10.1109/TVCG.2021.3119212
  url:
  volume:
  number:
  pages:
  month:

preprint: https://osf.io/j5g4b/ # here you can put all preprint links (arxiv.org, osf.io,...)

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project:

# Use this if you have an external project website
external-project: https://jku-vds-lab.at/fuzzy-spreadsheet/

# The reference to the video entry
video: 2021_fuzzy-spreadsheets_video
# The reference to the preview video entry
#preview-video:

# the prerint
pdf: 2020_preprint_fuzzy-spreadsheets.pdf
# A supplement PDF
supplement: https://osf.io/8ypux/

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/fuzzy-spreadsheet

abstract: "Spreadsheet-based tools provide a simple yet effective way of calculating values, which makes them the number-one choice for building and formalizing simple models for budget planning and many other applications. A cell in a spreadsheet holds one specific value and gives a discrete, overprecise view of the underlying model. Therefore, spreadsheets are of limited use when investigating the immanent uncertainties of such models and answering what-if questions. Existing extensions typically require a complex modelling process that cannot be smoothly embedded in a tabular layout. In Fuzzy Spreadsheet, a cell can hold and display a distribution of values. This integrated uncertainty handling immediately conveys sensitivity and robustness information. The fuzzification of the cells enables calculations not only with precise values but with distributions, and probabilities. We conservatively added and carefully crafted visuals to maintain the look and feel of traditional spreadsheet while facilitating what-if analyses. Given a user-specified reference cell, Fuzzy Spreadsheet automatically extracts and visualizes contextually relevant information, such as impact, uncertainty, and degree of neighborhood, for the selected and related cells. To evaluate its usability and the perceived mental effort required, we conducted a user study. The results show that our approach outperforms traditional spreadsheets in terms of answer correctness, response time, and perceived mental effort for almost all tasks tested."
# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements

This work was supported in part by the FFG, Contract No. 881844: "Pro2Future is funded within the Austrian COMET Program Competence Centers for Excellent Technologies under the auspices of the Austrian Federal Ministry for Climate Action, Environment, Energy, Mobility, Innovation and Technology, the Austrian Federal Ministry for Digital and Economic Affairs and of the Provinces of Upper Austria and Styria. COMET is managed by the Austrian Research Promotion Agency FFG."
Additional support was granted by the State of Upper Austria and the Austrian Federal Ministry of Education, Science and Research via the LIT -- Linz Institute of Technology (LIT-2019-7-SEE-117), and by the Federal State of Upper Austria (Human-Interpretable Machine Learning).
This paper was partly written in collaboration with the VRVis Competence Center. VRVis is funded by BMVIT, BMWFW, Styria, SFG and Vienna Business Agency in the scope of COMET—Competence Centers for Excellent Technologies (854174) which is managed by FFG.
