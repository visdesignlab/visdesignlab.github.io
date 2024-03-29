---
layout: publication
title: "Persist: Persistent and Reusable Interactions in Computational Notebooks"
key: 2023_preprint_persist
type: preprint
order: 2024-1

shortname: Persist
image: 2024_preprint_persist.png
image_large: 2024_preprint_persist_teaser.png

authors:
- kiran
- zcutler
- lex

journal-short: Preprint
year: 2024

bibentry: article
bib:
  booktitle: "Preprint"
  doi: 10.31219/osf.io/9x8eq
  # journal: IEEE Transactions on Visualization and Computer Graphics (VIS)
  # publisher: IEEE
  # doi: 10.1109/TVCG.2021.3114766
  # url:
  # volume: 28
  # number: 1
  # pages: 248-258
  # month:

# award: IEEE VIS 2021 Honorable Mention Award

# Links to a project hosted on VDL, or else externally on your own site


# Video entries, a preview , talk, and intro video. Vimeo IDs or youtube IDs are supported
# you need to pick either a vimeo or youtube ID. We definitely want a downloadable video too.

# videos:
#  - name: 'Loon Introduction'
#    youtube-id: Y7u3Kg3At9A
#    file: 2021_vis_loon.mp4
#  - name: 'Loon VIS Preview'
#    youtube-id: iRsL3WiZbhI
#    file: 2021_vis_loon_preview.mp4
#  - name: 'Loon VIS Talk'
#    youtube-id: Xz5VrBXk5J0
#    file: 2021_vis_loon_talk.mp4


# Video entry and preview video
videos:
 - name: 'Introduction'
   youtube-id: DXHXPvRHN9I
   file: 2024_preprint_persist.mp4



# Provide a preprint and supplement pdf

pdf: 2024_preprint_persist.pdf
# supplement: 2021_vis_loon_supplement.pdf

# Link to an official preprint server
preprint_server: https://doi.org/10.31219/osf.io/9x8eq


# # Extra supplements, such as talk slides, data sets, etc.

# supplements:
# - name: VIS Talk Slides
#   link: 2021_vis_loon_talk_slides.pdf

# Supplemental, cc-by images. Make caption brief (at most 60 chars)

# supplements:
# - name: Study Results and Example Notebooks
#  link: https://github.com/visdesignlab/persist-examples/


code: https://github.com/visdesignlab/persist/





abstract: "
<p>
Computational notebooks, such as Jupyter, support rich data visualization. However, even when visualizations in notebooks are interactive, they still are a dead end: Interactive data manipulations, such as selections, applying labels, filters, categorizations, or fixes to column or cell values, could be efficiently apply in interactive visual components, but interactive components typically cannot manipulate Python data structures. Furthermore, actions performed in interactive plots are volatile, i.e., they are lost as soon as the cell is re-run, prohibiting reusability and reproducibility. To remedy this, we introduce Persist, a family of techniques to capture and apply interaction provenance to enable persistence of interactions. When interactions manipulate data, we make the transformed data available in dataframes that can be accessed in downstream code cells. We implement our approach as a JupyterLab extension that supports tracking interactions in Vega-Altair plots and in a data table view. Persist can re-execute the interaction provenance when a notebook or a cell is re-executed enabling reproducibility and re-use. 
</p>
<p>
We evaluated Persist in a user study targeting data manipulations with 11 participants skilled in Python and Pandas, comparing it to traditional code-based approaches. Participants were consistently faster with Persist, were able to correctly complete more tasks, and expressed a strong preference for Persist.
</p>
"
---

# Acknowledgements

We would like to thank our interviewees for their time and participation in the study, and the Visualization Design Lab for the fruitful discussions and feedback.
Special thanks to Jake Wagoner for helping with the `intent_inference` library.
We gratefully acknowledge funding from the National Science Foundation (IIS 1751238 and CNS 213756).
