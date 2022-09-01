---
layout: project
type: project
image: img/computer-helios.jpg
title: "The hidden transcriptome in cerebrospinal fluid and an exploration of its role in Parkinson’s disease"
date: 2021
published: true
labels:
  - Transposable Elements
  - Cerebrospinal Fluid
  - Transcriptomics
  - STAR
  - R
  - Jinja2
  - Bioconductor
  - Parkinson's Disease
summary: "Conducted bioinformatics research over an eight-week period that looked into whether transposable elements make up part of the transcriptome that remains unmapped and whether transposable elements act as a potential biomarker in Parkinson's disease."
---

<img class="img-fluid" src="../img/computer-helios.jpg" alt="glasses in front of a computer screen with lines of code displayed">

I was part of the Helios Scholars program through the [Helios Education Foundation](www.helios.org) and the [Translational Genomics Research Institute](www.tgen.org), a part of [City of Hope](www.cityofhope.org). During this program, I worked on a research project in bioinformatics.

I looked into RNA in cerebrospinal fluid, which is extremely sparse. One ongoing question for those in neurogenomics is to understand what is in CSF. We know that there is something in the transcriptome that is mapping to something in the genome, but much of it is not understood, or "hidden" due to this sparcity. My project specifically looked at integrating the [TEtoolkit suite](https://hammelllab.labsites.cshl.edu/software/) in a Jinja2 pipeline and analyzing the outpute of this pipeline using [Bioconductor](https://www.bioconductor.org/) in R.

We wanted to know if transposable elements acted as potential biomarkers for Parkinson's disease, so analyses using DESeq2, pheatmap, and EnhancedVolcanoPlot compared those diagnosed with PD and healthy controls. Results require further analysis, but transposable elements were found in CSF. The abstract submitted for this project can be found on [TGen's website](https://www.tgen.org/education/alumni/2021/megan-hall/).

As this code is part of a larger project, I cannot provide it. Instead, here is some deidentified code to illustrate how DESeq2 is used:

{% gist dfe23b17333c95f04752c2642135859d %}
 
Source: <a href="https://github.com/PsychNStuff/BioNStuff/blob/main/Bioconductor_Basics.R">PsychNStuff/BioNStuff/blob/main/Bioconductor_Basics.R</a>
