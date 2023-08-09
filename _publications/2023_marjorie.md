---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Marjorie: Visualizing Type&nbsp;1 Diabetes Data to Support Pattern Exploration"
key: 2023_marjorie
# paper | preprint | poster
type: preprint
# optional url for a different site; defaults to data.jku-vds-lab.at
#paper_content_url: 


# The shortname is used for auto-generated titels
shortname: Marjorie

# TODO update images
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2023_marjorie_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2023_marjorie.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Anna Scimone
- eckelt
- streit
- hinterreiter

journal-short: OSF
year: 2023

bibentry: article
bib:
  journal: OSF Preprint
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi:  10.31219/osf.io/caj2n
  url:
  volume: 
  number: 
  pages: 
  month:

preprint: https://osf.io/caj2n # here you can put all preprint links (arxiv.org, osf.io,...)


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project: 

# Use this if you have an external project website
external-project: https://marjorie.jku-vds-lab.at/

videos:
 - name: 'Paper Video'
   youtube-id: https://youtu.be/wwFkrdqp4uo


pdf: 2023_marjorie.pdf

# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/marjorie/

supplement:
supplements:
 - name: Supplementary Material
   abslink: https://osf.io/34t8c/

abstract: "In this work we propose Marjorie, a visual analytics approach to address the challenge of analyzing patients' diabetes data during brief regular appointments with their diabetologists.
Designed in consultation with diabetologists, Marjorie uses a combination of visual and algorithmic methods to support the exploration of patterns in the data.
Patterns of interest include seasonal variations of the glucose profiles, and non-periodic patterns such as fluctuations around mealtimes or periods of hypoglycemia (i.e., glucose levels below the normal range).
We introduce a unique representation of glucose data based on modified horizon graphs and hierarchical clustering of adjacent carbohydrate or insulin entries.
Semantic zooming allows the exploration of patterns on different levels of temporal detail.
We evaluated our solution in a case study, which demonstrated Marjorie's potential to provide valuable insights into therapy parameters and unfavorable eating habits, among others.
The study results and informal feedback collected from target users suggest that Marjorie effectively supports patients and diabetologists in the joint exploration of patterns in diabetes data, potentially enabling more informed treatment decisions.
A free copy of this paper and all supplemental materials are available at <a href=\"https://osf.io/34t8c/\">https://osf.io/34t8c</a>.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---
