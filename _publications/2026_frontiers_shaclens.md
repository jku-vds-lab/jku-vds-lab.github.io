---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "SHACLens: A Visualization Workflow for SHACL Violation Exploration in Knowledge Graphs" # title of your publication
key: 2026_frontiers_shaclens

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
paper_content_url: https://public-pages-files-2025.frontiersin.org/journals/bioinformatics/articles/10.3389/fbinf.2026.1756507/
abstract: "Introduction: Validating large knowledge graphs with the Shapes Constraint Language (SHACL) often yields violation reports too large to interpret and trace to root causes, especially in industry-scale datasets such as pharmaceutical omics pipelines. Methods: We present SHACLens, an interactive visualization workflow developed with a major pharmaceutical partner that links ontology, instance data, and violation reports across multiple coordinated views. We contribute a practitioner-informed workflow co-designed with pharmaceutical data-analysis experts. A Node-Link View combines ontology and groups of equivalent violations, a projection view reveals clusters of nodes with similar errors, a LineUp table combines instance data with violation information, a Class Tree offers a class-hierarchy overview, and an integrated LLM assistant provides contextual explanations and can operate the system via natural-language commands. Results: Within this workflow, selections and filters propagate across views, exposing co-occurring errors and their likely upstream causes. Analysts iteratively identify violation clusters, inspect correlations, and trace the detailed cause of errors. Evaluation and implications: We evaluated SHACLens through an iterative expert-in-the-loop design process with the partner team and a qualitative study on a transcriptomics dataset containing 5,203 violating nodes with the same experts. In this study, SHACLens efficiently surfaced repeated sets of errors due to missing objects and schema inconsistencies, supporting goal-oriented analysis and serendipitous findings." # insert the abstract of your publication between the quotes; you can use html e.g. to make links (<a></a>) or generate bold (<b></b>) etc. text 

####


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: SHACLens
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2026_frontiers_shaclens_small.webp
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2026_frontiers_shaclens.webp

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- steinparz
- hinterreiter
- Labinot Bajraktari
- Vitaly Sedlyarov
- Markus J. Bauer
- Thomas Zichner
- streit
# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: Front. Bioinform.
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2026
non_group_project: false
# note: "Steinparz CA, Hinterreiter A, Bajraktari L, Sedlyarov V, Bauer MJ, Zichner T and Streit M (2026) SHACLens: a visualization workflow for SHACL violation exploration in knowledge graphs. Front. Bioinform. 6:1756507. doi: 10.3389/fbinf.2026.1756507"


# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: Frontiers in Bioinformatics
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 10.3389/fbinf.2026.1756507
  url: https://www.frontiersin.org/journals/bioinformatics/articles/10.3389/fbinf.2026.1756507
  volume: 6
  number: 
  pages: 1756507
  month: March

preprint:


# Use this if you have an external project website e.g. https://ordino.caleydoapp.org/
external-project: http://shaclens.jku-vds-lab.at/

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: pdf


# Link to the repository where the code is hostet
code: https://github.com/CursedSeraphim/bikg_app/

---
