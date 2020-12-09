---
layout: page
title: Mining tissue-specific signals from rare variants in the cancer genome
subtitle: Memorial Sloan Kettering Cancer Center & Pomona College
---

<figure>
  <p align="center">
  <img src="/assets/img/wordcloud.png" width="600" align="center">
  </p>
</figure>

**Check out my slide deck here: [QSURE Slide Deck: Metafeature Clustering](/assets/content/MSK Presentation slides.pdf)**

**Check out my project abstract: [QSURE Project Abstract](/assets/content/QSURE Abstract Edited.pdf)**

**Check out my [short video submission](https://youtu.be/5v99ahmq6pA) explaining my project to the Electronic Undergraduate Statistics Research Conference**

**Check out a report I wrote with [Oliver Chang](https://oliverc1623.github.io/): [Mining the Visible and Hidden Minigenome of the Cancer Mitochondrion](/Mitochondrial-Richness-Tech-Report-copy.html)** 

## QSURE: Using metafeature clustering to mine clinically-relevant signals from the cancer genome

Properly handling rare variant probabilities is an important challenge in precision oncology, particularly for the classification of tumors of unknown origin, testing for clonal relatedness, or in emerging diagnostic methods like liquid biopsy. During the summer of 2020, I worked in the Department of Epidemiology and Biostatistics at Memorial Sloan Kettering Cancer Center under the mentorship of Dr. Ronglai Shen and Dr. Saptarshi Chakraborty to extract tissue specific signals from rare mutations in the cancer genome. The vast majority of mutations in human cancer are rare: in The Cancer Genome Atlas (<a href="https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga">TCGA</a>), >90% of mutations occur only once. My mentors previously developed nonparametric Bayesian probability methods from computational linguistics and ecology to use rare mutation frequencies to estimate the probabilities of encountering new (or previously unseen variants) in major cancer genes under different tissue contexts (<a href="https://www.nature.com/articles/s41467-019-13402-z">Chakraborty et al., Nature Communications 10:1-9, 2019</a>). Under their mentorship, I developed a framework to extend this analysis to all genes in the human genome using machine learning methods and knowledge of features that drive mutational heterogeneity in cancer. I am continuing to work on this project for my senior thesis with the goal of developing an information-theoretic clustering approach to identify gene groups that contain rare variant patterns of high clinical relevance.

I conducted this research as part of Memorial Sloan Kettering's Quantitative Summer Undergraduate Research Experience (QSURE) Program. Through this program, I attended academic lectures, professional development workshops, and research ethics seminars. At the end of my internship, I gave a scientific presentation to the other QSURE fellows, their project advisors, and other researchers at Memorial Slaon Kettering Cancer Center. Linked above is the slide deck for my presentation and the research abstract that I authored if you want to learn more.

## CS145 Fall 2020: Mining the Visible and Hidden Minigenome of the Cancer Mitochondrion

<figure>
  <p align="center">
  <img src="/assets/img/mt landscape.png" width="600" align="center">
  </p>
</figure>

For my data mining final project, I extended my mentor's analysis to single nucleotide variant data from <a href="https://bioinformatics.mdanderson.org/public-software/tcma/">The Cancer Mitchondria Atlas</a> , to explore the landscape of mitochondrial mutation in human cancer. Unlike the nuclear genome, a fewer number of singleton variants were observed, fewer hitherto unseen variants were projected by future sequencing studies, and probabilities of encountering previously unseen variants were non-tissue specific. We observed highly tissue-specific hotspot mutations in regulatory regions and select members of the ETS. This project illustrated that the mutational vocabulary of the mitochondria is reduced relative to the nuclear genome.

## Senior Thesis: Feature Aggregation in the Cancer Genome

<figure>
  <p align="center">
  <img src="/assets/img/alg.png" width="600" align="center">
  </p>
</figure>

In order to boost tissue-specific capture from sparsely mutated genes in the cancer genome, I am developing feature aggregation algorithms to generate gene groups, or metagenes, that encode enhanced tissue-specific signals. Once candidate metagenes are developed, we will supply features to a classifier (multiclass logistic regression with LASSO penalty), and assess improvements in classifier performance.


