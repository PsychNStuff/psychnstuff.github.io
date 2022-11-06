---
layout: project
type: project
image: img/computer-helios.jpg
alt: glasses are placed in front of a computer with lines of code
title: "Transcriptomics, Genomics, and Neurological Disease"
date: 2021
published: true
labels:
  - Transposable Elements
  - Biofluids
  - Transcriptomics
  - STAR
  - R
  - Jinja2
  - Bioconductor
  - Parkinson's Disease
  - Alzheimer's Disease
  - Schizophrenia
summary: "I began learning about bioinformatics through the Helios Scholars program, an eight-week program that led to the completion of a project. Afterwards, I continued research in Neurogenomics, looking at the transcriptome, sparsity of biofluids, and looking into neurological disorders."
---

<img class="img-fluid" src="../img/computer-helios.jpg" alt="glasses in front of a computer screen with lines of code displayed">

I was part of the Helios Scholars program through the [Helios Education Foundation](https://www.helios.org/) and the [Translational Genomics Research Institute](https://www.tgen.org/), a part of [City of Hope](https://www.cityofhope.org/). During this program, I worked on a research project in bioinformatics.

I looked into RNA in cerebrospinal fluid, which is extremely sparse. One ongoing question for those in neurogenomics is to understand what is in CSF. We know that there is something in the transcriptome that is mapping to something in the genome, but much of it is not understood, or "hidden" due to this sparcity. My project specifically looked at integrating the [TEtoolkit suite](https://hammelllab.labsites.cshl.edu/software/) in a Jinja2 pipeline and analyzing the outpute of this pipeline using [Bioconductor](https://www.bioconductor.org/) in R.

We wanted to know if transposable elements acted as potential biomarkers for Parkinson's disease, so analyses using DESeq2, pheatmap, and EnhancedVolcanoPlot compared those diagnosed with PD and healthy controls. Results require further analysis, but transposable elements were found in CSF. The abstract submitted for this project can be found on [TGen's website](https://www.tgen.org/education/alumni/2021/megan-hall/).

After my work as a Helios Scholar was over, I became an intern and now work full-time at TGen. I have since worked with data related to neurodegenerative diseases such as Alzheimer's and Parkinson's Disease, Schizophrenia, and helped with projects related to ALS and COPD amongst many other diseases. I have also had the opportunity to look at RNA-seq data in many types of biofluid and tissue, such as urine, plasma, and CSF. Further, I have learned to use many packages with R programming and have helped to further add to our bioinformatics pipeline.

This is an example of some deidentified code to illustrate how DESeq2 is used:

{% gist dfe23b17333c95f04752c2642135859d %}
 
See <a href="https://github.com/PsychNStuff/BioNStuff/blob/main/Bioconductor_Basics.R">PsychNStuff/BioNStuff</a> for more!
