---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Provectories: Embedding-based Analysis of Interaction Provenance Data"
key: 2020_preprint_provectories
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.jku-vds-lab.at
paper_content_url: 


# The shortname is used for auto-generated titels
shortname: Provectories
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2021_tvcg_provectories.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2021_tvcg_provectories_teaser.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- walchshofer
- hinterreiter
- Kai Xu
- stitz
- streit 

journal-short: TVCG
year: 2021

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (Early Access)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 10.1109/TVCG.2021.3135697
  url:
  volume: 
  number: 
  pages: 
  month: December

preprint: https://osf.io/mtfxn/ # here you can put all preprint links (arxiv.org, osf.io,...)

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project: 

# Use this if you have an external project website
external-project: https://provectories.jku-vds-lab.at/

# The reference to the video entry
video: 
# The reference to the preview video entry
#preview-video:

# the prerint
pdf: 2020_preprint_provectories.pdf
# A supplement PDF
#supplement: 2017_preprint_taggle_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: 

abstract: "Understanding user behavior patterns and visual analysis strategies is a long-standing challenge. Existing approaches rely largely on time-consuming manual processes such as interviews and the analysis of observational data. While it is technically possible to capture a history of user interactions and application states, it remains difficult to extract and describe analysis strategies based on interaction provenance. In this paper, we propose a novel visual approach to the meta-analysis of interaction provenance. We capture single and multiple user sessions as graphs of high-dimensional application states. Our meta-analysis is based on two different types of two-dimensional embeddings of these high-dimensional states: layouts based on (i) topology and (ii) attribute similarity. We applied these visualization approaches to synthetic and real user provenance data captured in two user studies. From our visualizations, we were able to extract patterns for data types and analytical reasoning strategies."

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


# Acknowledgements

We would like to thank Kiran Gadhave and Alexander Lex for providing us with interaction provenance data for the second use case and for answering our questions. This work was supported by the FFG, Contract No. 881844: "Pro\textsuperscript{2}Future is funded within the Austrian COMET Program Competence Centers for Excellent Technologies under the auspices of the Austrian Federal Ministry for Climate Action, Environment, Energy, Mobility, Innovation and Technology, the Austrian Federal Ministry for Digital and Economic Affairs and of the Provinces of Upper Austria and Styria. COMET is managed by the Austrian Research Promotion Agency FFG." Additional support was granted by the Federal State of Upper Austria and the Austrian Federal Ministry of Education, Science and Research via the LIT -- Linz Institute of Technology (LIT-2019-7-SEE-117), and by the Federal State of Upper Austria (Human-Interpretable Machine Learning).