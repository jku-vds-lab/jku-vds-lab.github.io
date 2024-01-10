---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Loops: Leveraging Provenance and Visualization to Support Exploratory Data Analysis in Notebooks"
key: 2024_loops
# paper | preprint | poster
type: preprint
# optional url for a different site; defaults to data.jku-vds-lab.at
#paper_content_url: 


# The shortname is used for auto-generated titels
shortname: Loops

# TODO update images
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2024_loops_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2024_loops.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- eckelt
- Kiran Gadhave
- Alexander Lex
- streit

year: 2023
journal-short: OSF

bibentry: article
bib:
  journal: OSF Preprint
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi:  10.31219/osf.io/79eyn 
  url: https://doi.org/ 10.31219/osf.io/79eyn  
  volume: 
  number: 
  pages: 
  month:

preprint: https://osf.io/79eyn/ # here you can put all preprint links (arxiv.org, osf.io,...)


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project: 

# Use this if you have an external project website
external-project: https://mybinder.org/v2/gh/jku-vds-lab/loops/main?labpath=notebooks

pdf: 2024_loops.pdf

# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/loops

abstract: "
Exploratory data science work is often described as an iterative process with cycles of obtaining, cleaning, profiling, analyzing, and interpreting data. These cycles create challenges within the linear structure of computational notebooks, leading to code quality, recall, and reproducibility issues.
We present Loops, a set of visual support techniques for iterative and exploratory data analysis in computational notebooks. Loops leverages provenance information to provide direct feedback on the impact of changes made within the notebook. Through compact visual representations, we trace the evolution of the notebook over time, highlighting differences between versions. Detail views allow users to compare the cell content and output. Loops is compatible with various types of content present in notebooks, such as code, markdown, data, visualizations, or images.
Loops not only improves the reproducibility of notebooks, but also supports analysts during their data science work by showing the effects resulting from changes and facilitating the comparison of multiple versions. We demonstrate our approach's utility and potential impact through two use cases and feedback from notebook users spanning various backgrounds.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---


