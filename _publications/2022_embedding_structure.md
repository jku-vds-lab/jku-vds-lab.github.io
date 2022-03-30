---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Visual Exploration of Relationships and Structure in Low-Dimensional Embeddings"
#key: 
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.jku-vds-lab.at
#paper_content_url: 


# The shortname is used for auto-generated titels
shortname: Embedding Structure
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2022_embedding_structure_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2022_embedding_structure_large.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- eckelt
- hinterreiter
- adelberger
- walchshofer
- dhanoa
- humer
- heckmann
- steinparz
- streit

journal-short: IEEE TVCG
year: 2022

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (Early Access)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 10.1109/TVCG.2022.3156760
  url: 
  volume: 
  number: 
  pages: 
  month: March

preprint: https://osf.io/ujbrs # here you can put all preprint links (arxiv.org, osf.io,...)


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project: 

# Use this if you have an external project website
external-project: https://jku-vds-lab.at/apps/embeding-structure-explorer/

# (deprecated)
# # The reference to the video entry
# video: 2022_embedding_structure
# # The reference to the preview video entry
# #preview-video:

# the youtube-id of the video
youtube-id: yBCe8SqGwK8
# the youtube-id of the preview-video
preview-youtube-id: 


# the prerint
pdf: paper_2022_embedding_structure.pdf
#pdf_local: /assets/papers/paper_2022_embedding_structure
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
code: https://github.com/jku-vds-lab/projection-space-explorer

abstract: "In this work, we propose an interactive visual approach for the exploration and formation of structural relationships in embeddings of high-dimensional data. These structural relationships, such as item sequences, associations of items with groups, and hierarchies between groups of items, are defining properties of many real-world datasets. Nevertheless, most existing methods for the visual exploration of embeddings treat these structures as second-class citizens or do not take them into account at all. In our proposed analysis workflow, users explore enriched scatterplots of the embedding, in which relationships between items and/or groups are visually highlighted. The original high-dimensional data for single items, groups of items, or differences between connected items and groups is accessible through additional summary visualizations. We carefully tailored these summary and difference visualizations to the various data types and semantic contexts. During their exploratory analysis, users can externalize their insights by setting up additional groups and relationships between items and/or groups. We demonstrate the utility and potential impact of our approach by means of two use cases and multiple examples from various domains.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


# Acknowledgements

This work was supported in part by the Boehringer Ingelheim Regional Center Vienna, the State of Upper Austria and the Austrian Federal Ministry of Education, Science and Research via the LIT ⁠– Linz Institute of Technology (LIT-2019-7-SEE-117), the State of Upper Austria (Human-Interpretable Machine Learning), and the Austrian Science Fund (FWF DFH 23-N). This work was supported in part by the FFG, Contract No. 881844: "Pro2Future is funded within the Austrian COMET Program Competence Centers for Excellent Technologies under the auspices of the Austrian Federal Ministry for Climate Action, Environment, Energy, Mobility, Innovation and Technology, the Austrian Federal Ministry for Digital and Economic Affairs and of the Provinces of Upper Austria and Styria. COMET is managed by the Austrian Research Promotion Agency FFG.".
