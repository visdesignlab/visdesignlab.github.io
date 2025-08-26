---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "ReVISit 2: A Full Experiment Life Cycle User Study Framework"
key: 2025_vis_revisit
# paper | preprint | poster
type: paper
order: 2025-8

#paper_content_url: 


# The shortname is used for auto-generated titels
shortname: ReVISit

# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2025_vis_revisit.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 2025_vis_revisit_teaser.png

images:
  - path: 2025_vis_revisit_texture_study.png
    caption: ReVISit replay view showing the provenance history and current state of a participant
  - path: 2025_vis_revisit_timeline_view.png
    caption: ReVISit timeline view of participants who completed a study

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- zcutler
- wilburn
- Hilson Shrestha
- Yiren Ding
- bollen
- abrar
- he
- Andrew McNutt
- Lane Harrison
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

# Link to an official preprint server
preprint_server: https://arxiv.org/abs/2508.03876


# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award: IEEE VIS 2025 Best Paper Award

# Use this if you have an external project website
external-project: https://revisit.dev

pdf: 2025_vis_revisit.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
- name: Supplemental Material
  # Use link instead of abslink if you want to link to the master directory
  abslink: https://osf.io/e8anx
  # Defaults to a download icon, use this if you want a link-out icon
  linksym: true

# Link to the repository where the code is hostet
code: https://github.com/revisit-studies/study

videos:
 - name: 'Paper Video'
   youtube-id: 1t3nWNnv6BE
   file: 2025_vis_revisit.mp4 


abstract: "Online user studies of visualizations, visual encodings, and interaction techniques are ubiquitous in visualization research. Yet, designing, conducting, and analyzing studies effectively is still a major burden.Although various packages support such user studies, most solutions address only facets of the experiment life cycle, make reproducibility difficult, or do not cater to nuanced study designs or interactions. We introduce reVISit 2, a software framework that supports visualization researchers at all stages of designing and conducting browser-based user studies. ReVISit supports researchers in the design, debug & pilot, data collection, analysis, and dissemination experiment phases by providing both technical affordances (such as replay of participant interactions) and sociotechnical aids (such as a mindfully maintained community of support). It is a proven system that can be (and has been) used in publication-quality studies---which we demonstrate through a series of experimental replications. We reflect on the design of the system via interviews and an analysis of its technical dimensions. Through this work, we seek to elevate the ease with which studies are conducted, improve the reproducibility of studies within our community, and support the construction of advanced interactive studies.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.

---