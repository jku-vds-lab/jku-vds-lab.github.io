---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "What Happens to the Source Domain in Transfer Learning?" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "We investigate the impact of the source domain in supervised transfer learning, focusing on image classification. In particular, we aim to assess to which extent a fine-tuned model can still recognize the classes of the source domain. Furthermore, we want to understand how this ability impacts the target domain. We demonstrate how the retained knowledge about the old classes in a popular foundational model can interfere with the model’s ability to learn and recognize the new classes. This interference can incur significant implications and highlights an inherent shortcoming of supervised transfer learning." 

####
non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: What Happens in TL
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2023_what_happens_tl_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2023_what_happens_tl.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- alnouri
- Bilal Alsallakh

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ICLR ME-FoMo
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2023

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://sites.google.com/view/me-fomo2023

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: ICLR 2023 Workshop on Mathematical and Empirical Understanding of Foundation Models 
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 		# e.g.10.1109/TVCG.2020.3012063
  url: https://openreview.net/forum?id=BsqmRU5hkB
  volume: 
  number: 
  pages: 
  month: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: 2023_what_happens_tl.pdf
---

