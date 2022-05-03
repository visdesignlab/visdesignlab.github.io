---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "Reusing Interactive Analysis Workflows"
# Keys must be unique to each paper, see section below for more details
key: 2022_eurovis_reusing
# Select one of the options below
type: paper
order: 2022-03
# use this if this paper was previously a preprint and you need to preserve the old URL
# redirect_from: /publications/2017_preprint_lineage


# Auto-generates titles and alt-descriptors
shortname: Reusing Workflows
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2022_eurovis_reusing_intent.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2022_eurovis_reusing_intent.png

# Authors in the "database" can be used with just their person "key"
authors:
- kiran
- zcutler
- lex

# Include a shortened name for the journal or conference/proceedings
journal-short: CGF (EuroVis)
year: 2022

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"

bibentry: article
bib:
  journal: Computer Graphics Forum (EuroVis), to appear
  booktitle:
  url: https://osf.io/udqjr/
  doi:
  pages:
  award:

# Provide a link to the publisher's webpage if no DOI is available
publisherURL:

# Link to an official preprint server
preprint_server: https://osf.io/udqjr/

# Links to a project hosted on VDL, or else externally on your own site
#project: http://vdl.sci.utah.edu/data-hunch/
external-project: https://reapply-workflows.github.io/reapply-workflows/#/project

# Video entry and preview video


# Provide a preprint and supplement pdf
pdf: 2022_preprint_reusing_intent.pdf
supplement: 2022_eurovis_reusing_supplement.zip

# Extra supplements, such as talk slides, data sets, etc.
#supplements:
#- name: Vials Conference Talk Slides
  # Use link instead of abslink if you want to link to the master directory
 # abslink: http://vials.io/talk/
  # Defaults to a download icon, use this if you want a link-out icon
  #linksym: true

# Supplemental, cc-by images. Make caption brief (at most 60 chars)
images:
- path: 2022_eurovis_reusing_overview.png
  caption: Prototype to demonstrate the techniques to capture reusable workflows.
- path: 2022_eurovis_reusing_prediction_overlay.png
  caption: Predicted selections are shown as overlays on the visualization.
- path: 2022_eurovis_reusing_provenance.png
  caption: Provenance graph showing an analysis session.
- path: 2022_eurovis_reusing_agg.png
  caption: Prototype supports data manipulation like creating aggregates.
- path: 2022_eurovis_reusing_wf.png
  caption: Workflow editor allows the analyst to curate an analysis session into a workflow.
- path: 2022_eurovis_reusing_compare.png
  caption: Compare mode allows comparing the analysis session when applied to multiple datasets.
- path: 2022_eurovis_reusing_notebook.png
  caption: Workflows can be exported to jupyter notebook and reapplied.


# Link to the repository where the code is hosted
code: https://github.com/visdesignlab/reusing-intent/

abstract: "
Interactive visual analysis has many advantages, but an important disadvantage is that analysis processes and workflows cannot be easily stored and reused. This is in contrast to code-based analysis workflows, which can simply be run on updated datasets, and adapted when necessary. In this paper, we introduce methods to capture workflows in interactive visualization systems for different interactions such as selections, filters, categorizing/grouping, labeling, and aggregation. These workflows can then be applied to updated datasets, making interactive visualization sessions reusable. 
We demonstrate this specification using an interactive visualization system that tracks interaction provenance, and allows generating workflows from the recorded actions. The system can then be used to compare different versions of datasets and apply workflows to them. Finally, we introduce a Python library that can load workflows and apply it to updated datasets directly in a computational notebook, providing a seamless bridge between computational workflows and interactive visualization tools. 
"

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Acknowledgements

We wish to thank the reviewers for their feedback on our submission. We would also like to thank Derya Akbaba and Jack Wilburn from Visualization Design Lab for their help with feedback interviews. We gratefully acknowledge funding by the National Science Foundation (IIS 1751238).