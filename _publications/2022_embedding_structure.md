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
- Moritz Heckmann
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
#youtube-id: yBCe8SqGwK8 # commented out by stefan, due to new video sidepanel
# the youtube-id of the preview-video
#preview-youtube-id:  # commented out by stefan, due to new video sidepanel

# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

videos:
 - name: 'Paper Video'
   youtube-id: yBCe8SqGwK8
#  file: filename to look for, prefix http://data.jku-vds-lab.at/papers/
 - name: 'Talk @ ISMB BioVis 2022'
   youtube-id: 1S-IYcXWZmY
   description: 'Usage and all applications of the Projection Space Explorer can be found on the dedicated [Landing Page](https://jku-vds-lab.at/pse/).'
   extraurl: '[BioVis Program](http://biovis.net/2022/program_ismb/)'
   slides:
    - file: 2022_biovis_eckelt.pptx
    - file: 2022_biovis_eckelt.pdf

# the prerint
pdf: paper_2022_embedding_structure.pdf
#pdf_local: /assets/papers/paper_2022_embedding_structure
# A supplement PDF
#supplement: 2017_preprint_taggle_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: PSE Landing Page
  abslink: https://jku-vds-lab.at/pse/
  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/projection-space-explorer

abstract: "In this work, we propose an interactive visual approach for the exploration and formation of structural relationships in embeddings of high-dimensional data. These structural relationships, such as item sequences, associations of items with groups, and hierarchies between groups of items, are defining properties of many real-world datasets. Nevertheless, most existing methods for the visual exploration of embeddings treat these structures as second-class citizens or do not take them into account at all. In our proposed analysis workflow, users explore enriched scatterplots of the embedding, in which relationships between items and/or groups are visually highlighted. The original high-dimensional data for single items, groups of items, or differences between connected items and groups is accessible through additional summary visualizations. We carefully tailored these summary and difference visualizations to the various data types and semantic contexts. During their exploratory analysis, users can externalize their insights by setting up additional groups and relationships between items and/or groups. We demonstrate the utility and potential impact of our approach by means of two use cases and multiple examples from various domains.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
# Talk @ ISMB BioVis 2022 #, commented out by stefan to utilize the new video sidebar category

#<iframe width="560" height="315" src="https://www.youtube.com/embed/1S-IYcXWZmY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
#Usage and all applications of the Projection Space Explorer can be found on the dedicated [Landing Page](https://jku-vds-lab.at/pse/).
#**Slides**: [PPTX](https://data.jku-vds-lab.at/papers/2022_biovis_eckelt.pptx) \| [PDF](https://data.jku-vds-lab.at/papers/2022_biovis_eckelt.pdf)
#**BioVis Program**: [http://biovis.net/2022/program_ismb/](http://biovis.net/2022/program_ismb/)
---
# Acknowledgements

This work was supported in part by the Boehringer Ingelheim Regional Center Vienna, the State of Upper Austria and the Austrian Federal Ministry of Education, Science and Research via the LIT ⁠– Linz Institute of Technology (LIT-2019-7-SEE-117), the State of Upper Austria (Human-Interpretable Machine Learning), and the Austrian Science Fund (FWF DFH 23-N). This work was supported in part by the FFG, Contract No. 881844: "Pro2Future is funded within the Austrian COMET Program Competence Centers for Excellent Technologies under the auspices of the Austrian Federal Ministry for Climate Action, Environment, Energy, Mobility, Innovation and Technology, the Austrian Federal Ministry for Digital and Economic Affairs and of the Provinces of Upper Austria and Styria. COMET is managed by the Austrian Research Promotion Agency FFG.".


<script>if(!sessionStorage.getItem("_swa")&&document.referrer.indexOf(location.protocol+"//"+location.host)!== 0){fetch("https://counter.dev/track?"+new URLSearchParams({referrer:document.referrer,screen:screen.width+"x"+screen.height,user:"Klaus.Eckelt@gmail.com",utcoffset:"1"}))};sessionStorage.setItem("_swa","1");</script>
