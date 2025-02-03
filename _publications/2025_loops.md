---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Loops: Leveraging Provenance and Visualization to Support Exploratory Data Analysis in Notebooks"
key: 2025_loops
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.jku-vds-lab.at
#paper_content_url:

# The shortname is used for auto-generated titels
shortname: Loops

# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2025_loops_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2025_loops.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
  - eckelt
  - Kiran Gadhave
  - Alexander Lex
  - streit

journal-short: TVCG
year: 2025

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (Early Access)
  doi: 10.1109/TVCG.2024.3456186
  url:
  volume: 31
  number: 1
  pages: 1213-1223
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

videos:
  - name: "Paper Video"
    youtube-id: jCUwLm5wfNo

abstract: "Exploratory data science is an iterative process of obtaining, cleaning, profiling, analyzing, and interpreting data. This cyclical way of working creates challenges within the linear structure of computational notebooks, leading to issues with code quality, recall, and reproducibility. To remedy this, we present Loops, a set of visual support techniques for iterative and exploratory data analysis in computational notebooks. Loops leverages provenance information to visualize the impact of changes made within a notebook. In visualizations of the notebook provenance, we trace the evolution of the notebook over time and highlight differences between versions. Loops visualizes the provenance of code, markdown, tables, visualizations, and images and their respective differences. Analysts can explore these differences in detail in a separate view. Loops not only makes the analysis process transparent but also supports analysts in their data science work by showing the effects of changes and facilitating comparison of multiple versions. We demonstrate our approach's utility and potential impact in two use cases and feedback from notebook users from various backgrounds. This paper and all supplemental materials are available at https://osf.io/79eyn."
# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---
