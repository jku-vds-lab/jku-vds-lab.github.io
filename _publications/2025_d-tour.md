---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "D-Tour: Semi-Automatic Generation of Interactive Guided Tours forVisualization Dashboard Onboarding"
key: 2025_d-tour
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.jku-vds-lab.at
#paper_content_url:


# The shortname is used for auto-generated titels
shortname: D-Tour

# TODO update images
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2025_d-tour_small.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2025_d-tour.png

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- dhanoa
- hinterreiter
- Vanessa Fediuk
- Niklas Elmqvist
- Eduard Gröller
- streit

year: 2025
journal-short: IEEE VIS

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics
  booktitle:
  editor:
  publisher: 
  address:
  doi: 10.1109/TVCG.2024.3456347
  url: 
  volume: 31
  number:
  pages: 721-731
  month:

preprint: https://osf.io/preprints/osf/t5m3u # here you can put all preprint links (arxiv.org, osf.io,...)


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project:

# Use this if you have an external project website
external-project:

pdf: 2025_d-tour.pdf

# Link to the repository where the code is hostet
code: https://github.com/jku-vds-lab/dashboard-onboarding

abstract: "
  Onboarding a user to a visualization dashboard entails explaining its various components, including the chart types used, the data loaded, and the interactions available.
  Authoring such an onboarding experience is time-consuming and requires significant knowledge, and little guidance exists on how best to complete this task. Depending on their levels of expertise, end users being onboarded to a new dashboard can be either confused and overwhelmed or disinterested and disengaged. We propose interactive dashboard tours (D-Tours) as semi-automated onboarding experiences that preserve the agency of users with various levels of expertise to keep them interested and engaged. Our interactive tours concept draws from open-world game design to give the user freedom in choosing their path through onboarding. We have implemented the d-tour concept in a tool called D-Tour Prototype, which allows authors to craft custom d-tours from scratch or using automatic templates.
   Automatically generated tours can still be customized to use different media (e.g., video, audio, and highlighting) or new narratives to produce an onboarding experience tailored to an individual user.  We demonstrate the usefulness of d-tours through use cases and expert interviews. Our evaluation shows that authors found the automation in the D-Tour Prototype helpful and time-saving, and users found the created tours engaging and intuitive.
  This paper and all supplemental materials are available at https://osf.io/6fbjp/.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---


# Acknowledgements
We thank Ivaletta Shakhova from Technical University, Vienna, for her contribution and support in the design and development of the D-Tour Prototype.
This work was supported by the Austrian Science Fund (FWF DFH 23–N), Villum Fonden (Villum Investigator grant VL-54492, Denmark), and the Austrian Research Promotion Agency (FFG 881844, FFG 879730). Any opinions, findings, and conclusions or recommendations expressed here are those of the authors and do not necessarily reflect the views of the funding agencies.