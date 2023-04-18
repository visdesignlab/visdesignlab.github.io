---
layout: publication
# Quotes make the : possible, otherwise you can type this without quotes
title: "Composer: Visual Cohort Analysis of Patient Outcomes"
# Keys must be unique to each paper, see section below for more details
key: 2019_aci_composer
# Select one of the options below
type: paper 
order: 2019-05
# use this if this paper was previously a preprint and you need to preserve the old URL
# redirect_from: /publications/2017_preprint_lineage
# Uncomment the line below for publications which should only appear on a personal webpage
# personal: y

# Auto-generates titles and alt-descriptors
shortname: Composer
# Add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/publications/
image: 2019_aci_composer.png
# Add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/publications/
image_large: 2019_aci_composer_teaser.png

# Authors in the "database" can be used with just their person "key"
authors:
- rogers
- Nicholas Spina
- Ashley Neese
- Rachel Hess
- Darrel Brodke
- lex

# Include a shortened name for the journal or conference/proceedings
journal-short: ACI
year: 2019

# Create BibTeX info, using one of the entry choices
# Articles have a "journal", and inproceedings have a "booktitle"
# Preprints are articles with the location of preprint mentioned in "journal"
# You can remove fields you don't need, or else leave them blank
# Try to include a DOI, or use the publisher URL below
# Specify new BibTeX fields by adding a new key and value inside "bib:"
bibentry: article
bib:
  journal: Applied Clinical Informatics
  #booktitle: Special Section":" Visual Analytics in Healthcare
  editor: 
  publisher: American Medical Informatics Association
  address: 
  doi: 10.1055/s-0039-1687862
  url: 
  volume: 10
  number: 02
  pages: 278-285
  month: 
  pmcid: 

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
#award: EuroVis 2016 Honorable Mention Award

# Provide a link to the publisher's webpage if no DOI is available
publisherURL: 

# Link to an official preprint server
preprint_server: https://arxiv.org/abs/1809.08177

# Links to a project hosted on VDL, or else externally on your own site
project: 
#external-project: https://pathfinder.caleydoapp.org/

# Video entry and preview video
#video: 2016_eurovis_pathfinder_video
#preview-video: 2016_eurovis_pathfinder_video_preview

# Provide a preprint and supplement pdf
pdf: 2019_aci_composer.pdf
#supplement: 2016_eurovis_pathfinder_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
#supplements:
#- name: Vials Conference Talk Slides
  # Use link instead of abslink if you want to link to the master directory
 # abslink: http://vials.io/talk/
  # Defaults to a download icon, use this if you want a link-out icon
  #linksym: true

# Link to the repository where the code is hosted
code: https://github.com/visdesignlab/Composer/

abstract: "
<p>
<b>Objective.</b> Visual cohort analysis utilizing electronic health record data has
become an important tool in clinical assessment of patient outcomes. In this
paper, we introduce Composer, a visual analysis tool for orthopedic surgeons to
compare changes in physical functions of a patient cohort following various
spinal procedures. The goal of our project is to help researchers analyze
outcomes of procedures and facilitate informed decision-making about treatment
options between patient and clinician. </p>

<p>
<b>Methods.</b> In collaboration with Orthopedic surgeons and researchers, we defined domain-specific user
requirements to inform the design. We developed the tool in an iterative
process with our collaborators to develop and refine functionality. With
Composer, analysts can dynamically define a patient cohort using demographic
information, clinical parameters, and events in patient medical histories and
then analyze patient-reported outcome scores for the cohort over time, as well
as compare it to other cohorts. Using Composer's current iteration, we provide
a usage scenario for use of the tool in a clinical setting. 
</p>
<p><b>Conclusion.</b>
We have developed a prototype cohort analysis tool to help clinicians assess patient
treatment options by analyzing prior cases with similar characteristics. Though
Composer was designed using patient data specific to Orthopedic research, we
believe the tool is generalizable to other healthcare domains. A long term goal
for Composer is to develop the application into a shared decision-making tool
that allows translation of comparison and analysis from a clinician facing
interface into visual representations to communicate treatment options to
patients.
</p>
"

# After the ---, you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---

# Note
This is the journal version of a [previously published workshop paper](../2018_vahc_composer).

# Acknowledgements

We thank Sahar Mehrpour for initial data analysis and
implementation. This project is funded by the Orthopaedic
Research Center and NSF IIS 1751238.