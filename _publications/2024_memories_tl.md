---
layout: publication # do not change

#### these fields are mandatory. please fill them out
title: "Detrimental Memories in Transfer Learning" # title of your publication 

# choose one of the following types:
# "paper": Peer-Reviewed Journal and Conference Papers
# "preprint": Preprint
# "thesis": Thesis (e.g. Master/PhD Thesis)
type: paper
abstract: "The source domain in transfer learning provides essential features that enable effective and data-efficient learning on the target task. Typically, the finetuning process does not explicitly account for how the knowledge about the source domain interacts with the target task. We demonstrate how that knowledge can interfere with the target task leading to negative transfer. Specifically, certain memories about the source domain can distract the finetuned model in certain inputs. We provide a method to analyze those memories in typical foundational models and to surface potential failure cases of those models. This analysis helps model developers explore remedies for those failure cases." 

####
non_group_project: True


#### the following fields are optional, but it is recommended to enter as much information as possible
# The shortname is used for auto-generated titels. e.g. ConfusionFlow
shortname: Memories in TL
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow.png
image: 2024_memories_tl_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/ e.g. 2020_tvcg_confusionflow_teaser.png
image_large: 2024_memories_tl.png

# Authors in the "database" can be used with just the key that is specified in the corresponding .md file (usually it is the lastname in lower case e.g. doe). Authors that do not have an individual page here should be stated with their full name (e.g. John Doe)
# each author is one item in the list. the list is enumerated with dashes ("-")
# e.g:
# authors:
# - doe # .md file exists for this person
# - streit # .md file exists for this person
# - Max Mustermann # there is no .md file for this person.
authors:
- alnouri
- Timothy J Wroge
- Bilal Alsallakh

# abreviation of the journal/conference ... e.g. IEEE TVCG
journal-short: ICML TF2M
# when was this publication written/ when was the publication accepted (e.g. 2020)
year: 2024

# if you have an explicit page you want to reference, use this tag; otherwise it will be generated from your doi
publisherurl: https://sites.google.com/view/tf2m?pli=1

# what is the publication type and other bib specific properties
bibentry: article
bib:
  journal: ICML 2024 Workshop on Theoretical Foundations of Foundation Models 
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 		# e.g.10.1109/TVCG.2020.3012063
  url: https://openreview.net/forum?id=mALjVQZV8N
  volume: 
  number: 
  pages: 
  month: 

# the name of your publication pdf e.g. 2020_tvcg_confusionflow.pdf; this is usually uploaded to the caleydo aws server
pdf: 2024_memories_tl.pdf
---

