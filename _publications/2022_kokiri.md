---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Kokiri: Random-Forest-Based Comparison and Characterization of Cohorts"
key: 2022_kokiri
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.jku-vds-lab.at
#paper_content_url: 


# The shortname is used for auto-generated titels
shortname: Kokiri
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2022_kokiri_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2022_kokiri.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- eckelt
- adelberger
- Markus J. Bauer
- Thomas Zichner
- streit

journal-short: vis-biomed-ai
year: 2022

bibentry: article
bib:
  journal: IEEE VIS Workshop on Visualization in Biomedical AI
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 10.1101/2022.08.16.503622
  url: https://www.biorxiv.org/content/10.1101/2022.08.16.503622
  volume: 
  number: 
  pages: 
  month: #Oktober #TODO

preprint: https://www.biorxiv.org/content/10.1101/2022.08.16.503622 # here you can put all preprint links (arxiv.org, osf.io,...)


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project: 

# Use this if you have an external project website
external-project: https://kokiri.jku-vds-lab.at/

videos:
 - name: 'Paper Video'
   youtube-id: 94W9pIsYq9g
#  file: filename to look for, prefix http://data.jku-vds-lab.at/papers/
 - name: 'Talk @ IEEE VIS Workshop on Visualization in Biomedical AI 2022'
   youtube-id: -jBODbF5jf4
   #description: 'Trololo'
   extraurl: '[Workshop Homepage](https://vis-biomed-ai.github.io/)'
   slides:
    - file: 2022_ieeevis_kokiri.pptx
    - file: 2022_ieeevis_kokiri.pdf


# the prerint
pdf: 2022_kokiri.pdf

# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/kokiri/

abstract: "We propose an interactive visual analytics approach to characterizing and comparing patient subgroups (i.e., cohorts). Despite having the same disease and similar demographic characteristics, patients respond differently to therapy. One reason for this is the vast number of variables in the genome that influence a patient's outcome. Nevertheless, most existing tools do not offer effective means of identifying the attributes that differ most, or look at them in isolation and thus ignore combinatorial effects. To fill this gap, we present Kokiri, a visual analytics approach that aims to separate cohorts based on user-selected data, ranks attributes by their importance in distinguishing between cohorts, and visualizes cohort overlaps and separability. With our approach, users can additionally characterize the homogeneity and outliers of a cohort. To demonstrate the applicability of our approach, we integrated Kokiri into the Coral cohort analysis tool to compare and characterize lung cancer patient cohorts.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---
# Acknowledgements

The authors acknowledge the American Association for Cancer Research and its financial and material support in the development of the AACR Project GENIE registry, and members of the consortium for their commitment to open data. Interpretations are the responsibility of study authors.

This work was supported in part by the Boehringer Ingelheim Regional Center Vienna, the State of Upper Austria, and the Austrian Federal Ministry of Education, Science and Research via the LIT -- Linz Institute of Technology (LIT-2019-7-SEE-117), the State of Upper Austria (Human-Interpretable Machine Learning), and the Austrian Science Fund (FWF DFH 23-N). 

