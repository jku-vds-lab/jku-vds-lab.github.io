---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Explainable Long- and Short-term Pattern Detection in Projected Sequential Data"
key: 2023_pattern_detection_xai
# paper | preprint | poster
type: preprint
# optional url for a different site; defaults to data.jku-vds-lab.at
#paper_content_url: 


# The shortname is used for auto-generated titels
shortname:
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2023_pattern_detection_xai_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2023_pattern_detection_xai.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Matthias Bittner
- hinterreiter
- eckelt
- streit

journal-short: XAI-TS
year: 2023

bibentry: inproceedings
bib:
  journal: "ECML PKDD Workshop on Explainable AI for Time Series: Advances and Applications (XAI-TS '23, to appear)"
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 
  url:
  volume: 
  number: 
  pages: 
  month:

#preprint: https://www.biorxiv.org/content/10.1101/2022.08.16.503622 # here you can put all preprint links (arxiv.org, osf.io,...)


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

# uncomment the "hide" property, if you do not want the publication to be displayed on the website (usually you don't need this)
# hide: True
# uncomment the "non_group_project" property, if you only want the publication to be displayed on your personal page (i.e. publications where you contributed, but does not have anything to do with the Vis Group e.g. Master Thesis,...)
# non_group_project: True



# the prerint
pdf: 2023_pattern_detection_xai.pdf

# Link to the repository where the code is hostet
code:

abstract: "Combining explainable artificial intelligence and information visualization holds great potential for users to understand and reason about complex multidimensional sequential data. This work proposes a semi-supervised two-step approach for extracting long- and short-term patterns in low-dimensional representations of sequential data.
First, unsupervised sequence clustering is used to identify long-term patterns. Second, these long-term patterns serve as supervisory information for training a self-attention-based sequence classification model. The resulting feature embedding is used to identify short-term patterns.
The approach is validated on a self-generated dataset consisting of heart-shaped paths with different sampling rates, rotations, scales, and translations. The results demonstrate the approach's effectiveness for clustering semantically similar paths and/or path sequences. This detection of both global long-term patterns and local short-term patterns facilitates the understanding and reasoning about complex multidimensional sequential data.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---
