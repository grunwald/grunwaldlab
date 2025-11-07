---
title: 'Preprint and first release of PathogenSurveillance'
subtitle: 'We are pleased to announce the first release and pre-print of our nextflow pipeline :gear:'
summary: nf-core/pathogensurveillance is a population genomics pipeline for pathogen identification, variant detection, and biosurveillance. The pipeline accepts paths to raw reads for one or more organisms and creates reports in the form of an interactive HTML document. Significant features include the ability to analyze unidentified eukaryotic and prokaryotic samples, creation of reports for multiple user-defined groupings of samples, automated discovery and downloading of reference assemblies from NCBI RefSeq, and rapid initial identification based on k-mer sketches followed by a more robust multi gene phylogeny and SNP-based phylogeny.

authors:
- admin
tags:
- Academic
categories: []
date: "2025-10-30T00:00:00Z"
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

---

**Release of PathogenSurveillance**

We are pleased to announce the first release of [nf-core/pathogensurveillance](https://nf-co.re/pathogensurveillance/1.0.0/) version 1.0 and the [bioRxiv prepint](https://doi.org/10.1101/2025.10.31.685798). 

Whole genome sequencing (WGS) offers a comprehensive, organism-agnostic method that effectively meets the need for efficient, reliable, and standardized responses to emerging threats from pathogens and pests. Here, we present **PathogenSurveillance**, an open-source and automated Nextflow pipeline for population genomic analyses of WGS data. It is designed with features tailored for biosurveillance and is suitable for in-field or point-of-care diagnostics. **PathogenSurveillance** is flexible, accommodating short- and long-read datasets and mixed samples of prokaryotes and/or eukaryotes. It automates all steps, including reference identification and retrieval from the NCBI Assembly database, and produces customizable interactive reports with summaries, phylogenetic trees, and minimum spanning networks that enable species and subspecies level identification. It also outputs quality control metrics and organizes genomic data hierarchically to facilitate downstream analyses. The pipeline runs on any Linux-based system and minimizes the need for advanced computational expertise. Source code is available on GitHub under the open-source MIT license. The pipeline expands the toolkit for real-time biosurveillance, enabling rapid detection and monitoring of pathogens and pests for rapid response to novel variants.
