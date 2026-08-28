---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "EventColumn: Integrating Event Sequences into Tabular Visualizations" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "We introduce EventColumn, a new column type that integrates event-sequence data with heterogeneous tabular attributes into a single unified table. EventColumn lets analysts compare event sequences alongside numerical, categorical, and temporal attributes at both instance and group levels, offering a compressed overview, heatmap group summaries, alignment by event types, and boxplots of similar historical items. We developed EventColumn together with collaborators from the steel industry to facilitate the analysis of production events and warehouse logistics, but the solution generalizes to a wide range of event sequence datasets with additional tabular attributes. Unlike most existing approaches that compare either event sequences or tables, EventColumn supports simultaneous comparison of both. We demonstrate its integration with Taggle and Microsoft Power BI on data from steel production logistics and on a public e-commerce dataset."

####


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: eventcolumn
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2026_eventcolumn_small.jpg
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2026_eventcolumn.jpg

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- Jakob Zethofer
- hinterreiter
- steinparz
- Lukas Schiefermüller
- Belgin Mutlu
- streit
# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: IEEE VIS 2026 - Short Papers
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2026


# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal:
  booktitle: IEEE VIS 2026 - Short Papers (to appear)
  editor: 
  publisher: 
  address: 
  doi: 10.48550/arXiv.2605.06065
  url: https://arxiv.org/abs/2605.06065
  volume: 
  number: 
  pages: 
  month:

paper_content_url: 


# Use this if you have an external project website e.g. https://ordino.caleydoapp.org/
external-project: https://jku-vds-lab.at/pro2future-event-table-viewer

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: 2026_eventcolumn.pdf


# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/pro2future-event-table-viewer

---
