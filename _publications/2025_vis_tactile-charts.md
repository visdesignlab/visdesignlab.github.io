---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "Using Tactile Charts to Support Comprehension and Learning of Complex Visualizations for Blind and Low-Vision Individuals"
key: 2025_vis_tactile-charts
# paper | preprint | poster
type: paper
order: 2025-6

#paper_content_url: 


# The shortname is used for auto-generated titles
shortname: Tactile Charts

# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2025_vis_tactile-charts.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2025_vis_tactile-charts_teaser.png


external-project: https://vdl.sci.utah.edu/tactile-charts/
# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
  - he
  - Maggie McCracken
  - Daniel Hajas
  - Sarah Creem-Regehr
  - lex


year: 2026
journal-short: IEEE VIS

bibentry: article
bib:
  journal: IEEE Transactions on Visualization and Computer Graphics (VIS)
  booktitle: 
  editor: 
  publisher: 
  address: 
  doi: 
  url: 
  volume: 32
  number: 
  pages: 
  month: jan

preprint_server: https://arxiv.org/abs/2507.21462



# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:


pdf: 2025_vis_tactile-charts.pdf

supplement: 2025_vis_tactile-charts_supplement.zip

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Supplementary Material OSF
  # Use link instead of abslink if you want to link to the master directory
  abslink: https://osf.io/9dwgq/
  # Defaults to a download icon, use this if you want a link-out icon
  linksym: true


images:
  - path: 2025_vis_tactile-charts_initial-design-no-overlap.png
    caption: Initial design of the tactile charts for the four chart types.
  - path: 2025_vis_tactile-charts_initial-and-final-design.png
    caption: Initial and final designs of the tactile charts for the four chart types.


code: https://github.com/visdesignlab/tactile-charts/

abstract: "
We investigate whether tactile charts support comprehension and learning of complex visualizations for blind and low-vision (BLV) individuals and contribute four tactile chart designs and an interview study. Visualizations are powerful tools for conveying data, yet BLV individuals typically can rely only on assistive technologies—primarily alternative texts—to access this information. Prior research shows the importance of mental models of chart types for interpreting these descriptions, yet BLV individuals have no means to build such a mental model based on images of visualizations. Tactile charts show promise to fill this gap in supporting the process of building mental models. Yet studies on tactile data representations mostly focus on simple chart types, and it is unclear whether they are also appropriate for more complex charts as would be found in scientific publications. Working with two BLV researchers, we designed 3D-printed tactile template charts with exploration instructions for four advanced chart types: UpSet plots, violin plots, clustered heatmaps, and faceted line charts. We then conducted an interview study with 12 BLV participants comparing whether using our tactile templates improves mental models and understanding of charts and whether this understanding translates to novel datasets experienced through alt texts. Thematic analysis shows that tactile models support chart type understanding and are the preferred learning method by BLV individuals. We also report participants' opinions on tactile chart design and their role in BLV education.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---

# Acknowledgements

We thank Gordon Legge for his valuable feedback on our tactile chart design. We appreciate Jinol Shah for digital modeling, Omar Shami and Ryan Manwill for 3D printing, Nathan Galli for chart photography, and Iara Delgado for transcription corrections. We gratefully acknowledge Funding by the Chan Zuckerberg Initiative.