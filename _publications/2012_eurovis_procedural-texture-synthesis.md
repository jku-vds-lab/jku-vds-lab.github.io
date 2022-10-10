---
layout: publication
title: "Procedural Texture Synthesis for Zoom-Independent Visualization of Multivariate Data"
key: 2012_eurovis_procedural-texture-synthesis
permalink: /publications/2012_eurovis_procedural-texture-synthesis/
type: paper

shortname: 
image: 2012_eurovis_procedural-texture-synthesis.png
image_large: 2012_eurovis_procedural-texture-synthesis-teaser.png

authors:
- Rostislav Klebnikov
- Bernhard Kainz
- Markus Steinberger
- streit
- Dieter Schmalstieg

# Include a shortened name for the journal or conference/proceedings
journal-short: CG (EuroVis '12)
year: 2012

bibentry: article
bib:
  journal: Computer Graphics Forum (EuroVis '12)
  doi: 10.1111/j.1467-8659.2012.03127.x
  volume: 31
  number: 3
  pages: 1355--1364

award:

non_group_project: True

project: 

video: 2012_eurovis_procedural-texture-synthesis_video
preview-video:


pdf:  2012_eurovis_procedural-texture-synthesis.pdf
supplement:
bibtex:  2012_eurovis_procedural-texture-synthesis.bib

abstract: "Simultaneous visualization of multiple continuous data attributes in a single visualization is a task that is important for many application areas. Unsurprisingly, many methods have been proposed to solve this task. However, the behavior of such methods during the exploration stage, when the user tries to understand the data with panning and zooming, has not been given much attention. In this paper, we propose a method that uses procedural texture synthesis to create zoom-independent visual- izations of three scalar data attributes. The method is based on random-phase Gabor noise, whose frequency is adapted for the visualization of the first data attribute. We ensure that the resulting texture frequency lies in the range that is perceived well by the human visual system at any zoom level. To enhance the perception of this at- tribute, we also apply a specially constructed transfer function that is based on statistical properties of the noise. Additionally, the transfer function is constructed in a way that it does not introduce any aliasing to the texture. We map the second attribute to the texture orientation. The third attribute is color coded and combined with the texture by modifying the value component of the HSV color model. The necessary contrast needed for texture and color perception was determined in a user study. In addition, we conducted a second user study that shows significant advantages of our method over current methods with similar goals. We believe that our method is an important step towards creating methods that not only succeed in visualizing multiple data attributes, but also adapt to the behavior of the user during the data exploration stage."

---

# Acknowledgements
This research was funded by the Austrian Science Fund (FWF): P23329 and the Austrian Research Promotion Agency (FFG) under the BRIDGE program: project 822702 (NARKISSOS).
