---
layout: post
title: Surveying the visible and hidden mutational landscape of the cancer mitochondrion
subtitle: My first blog post
cover-img: /assets/img/landscape1.jpeg
thumbnail-img: /assets/img/mitochondria_stained.jpeg
share-img: /assets/img/mitochondria_stained.jpeg
tags: [nonparametric methods, mitochondria, cancer, mutation]
---
Thank you to my friend Nate Stringham for sending me [this article](https://www.blopig.com/blog/2020/12/casp14-what-google-deepminds-alphafold-2-really-achieved-and-what-it-means-for-protein-folding-biology-and-bioinformatics/) on Google Alphabet's recent development of their new AlphaFold2 Deep Learning prediction method for solving the protein structure problem! The cover image (above) shows the sum Z-score performance (essentially how much each method outperforms the average over a number of protein structures): group 427, AlphaFold2, shows a remarkable boost relative to all the other methods!

As an unknowledgeable enthusiast of proteomics, I found this blogpost was a really nice (and not too technical) distillation of the major findings at the 14th Critical Assessment of Structural Prediction (CASP) Competition, of which AlphaFold2 was the runaway winner.

![AlphaFold2 prediction (blue) vs the known target protein structure T1046s1 (red) illustrating remarkable prediction!](/assets/img/fold.png)

Here were my main takeaways from the article, categorized by what AlphaFold2 does well vs where it has room for improvement vs outstanding questions:
- AlphaFold2 successes
  - AlphaFold2 offers the best computational prediction of peptide secondary structure seen to date, vastly outperforming existing methods.
  - Accurate protein structure characterization requires crystallography, which can take years and millions of dollars to complete. AlphaFold2 offers a much faster and cheaper solution to these tasks. 
  - AlphaFold2 identified mistakes in protein structures determined by crystallography!!!
- AlphaFold2 areas for improvement
  - AlphaFold2 provides a *general* but not *universal* solution to the protein structure problem. Protein structure databases are biased towards proteins that are easier to crystallize and aren't representative of the more complex array of proteins uncharacterized in the wild.
  - AlphaFold2 does not address the *protein folding problem*, which involves the assembly of multiple subchains guided by proteins milieu (i.e. protein-protein interactions)
- Alphafold2 outstanding questions
  - Will Alphabet make AlphaFold2 accessible as open source code or will they commercially liscence it? Will it be available as an API for scientists?
  - How computationally intensive is running AlphaFold2? How prohibitive will the computational requirements be to scientists who want to use this method?
  
The implications for protein biology and bioinformatics are immense, as AlphaFold2 could permit graduation from the protein structure problem to higher order problems about protein conformation and interactions.

Also as highlighted in ths article, the implications for academic research are also startling. AlphaFold2's group was small, nimble, and backed by Google, allowing it the opportunity to try many approaches with essentially unlimited financial and computational resources. Can academic teams keep pace with industry research in these kind of moonshot problems? Should academia consider restructuring research teams in the likeness of AlphaFold2's team?
