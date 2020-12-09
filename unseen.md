---
layout: page
title: Using metafeature clustering to mine signals from rare variants in the cancer genome
sutitle: Memorial Sloan Kettering Cancer Center & Pomona College
---

<p align="center">
    <img src="images/Word Cloud.jpeg" width="450" height="450" />
    <figcaption><i>This word cloud was generated from The Cancer Genome Atlas home webpage. Our analysis considers a kind of "mutational wordcloud", and uses methods developed in computational linguistics to calculate probabilities of encountering rare mutations (or green words) with the goal of attributing primary sites to cancer. </i></figcaption>
</p>

**Check out my slide deck here: [QSURE Slide Deck: Metafeature Clustering](/MSK Presentation slides.pdf)**

**Check out my project abstract: [QSURE Project Abstract](/QSURE Abstract Edited.pdf)**

**Check out my [short video submission](https://youtu.be/5v99ahmq6pA) explaining my project to the Electronic Undergraduate Statistics Research Conference**

**Check out a report I wrote with [Oliver Chang](https://oliverc1623.github.io/): [Mining the Visible and Hidden Minigenome of the Cancer Mitochondrion](/mito_rev.html)** 

Identifying a cancer's tissue of origin from its genome sequence is an important challenge in precision oncology, particularly for the classification of tumors of unknown origin, diagnosis of metastatic disease, or in emerging diagnostic methods like liquid biopsy. During the summer of 2020, I worked in the Department of Epidemiology and Biostatistics at Memorial Sloan Kettering Cancer Center under the mentorship of Dr. Ronglai Shen and Dr. Saptarshi Chakraborty to extract tissue specific signals from rare mutations in the cancer genome. The vast majority of mutations in human cancer are rare: in The Cancer Genome Atlas (<a href="https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga">TCGA</a>), >90% of mutations occur only once. My mentors previously developed nonparametric Bayesian probability methods from computational linguistics and ecology to use rare mutation frequencies to estimate the probabilities of encountering new (or previously unseen variants) in major cancer genes under different tissue contexts (<a href="https://www.nature.com/articles/s41467-019-13402-z">Chakraborty et al., Nature Communications 10:1-9, 2019</a>). Under their mentorship, I developed a framework to extend this analysis to all genes in the human genome using machine learning methods and knowledge of features that drive mutational heterogeneity in cancer. I am continuing to work on this project for my senior thesis with the goal of developing an information-theoretic clustering approach to identify gene groups that contain rare variant patterns of high clinical relevance.

I extended my mentor's analysis to somatic variant mutation data from <a href="https://bioinformatics.mdanderson.org/public-software/tcma/">The Cancer Mitchondria Atlas</a> , to explore whether unseen variant probabilities in mitochondrial genome features encoded tissue specific signals. This represented a further effort to use the preponderance of previously neglected mutational information for important clinical tasks. 

I conducted this research as part of Memorial Sloan Kettering's Quantitative Summer Undergraduate Research Experience (QSURE) Program. Through this program, I attended academic lectures, professional development workshops, and research ethics seminars. At the end of my internship, I gave a scientific presentation to the other QSURE fellows, their project advisors, and other researchers at Memorial Slaon Kettering Cancer Center. Linked above is the slide deck for my presentation and the research abstract that I authored if you want to learn more.
