---
title: "A Hybrid Learning-to-Optimize Framework for Mixed-Integer Quadratic Programming"
collection: publications
category: conferences
permalink: /publication/2025-11-11-hybrid-l2o-miqp
excerpt: 'This paper presents a novel hybrid learning-to-optimize framework for solving mixed-integer quadratic programming (MIQP) problems, combining the strengths of traditional optimization techniques with modern machine learning approaches to enhance solution efficiency and accuracy.'
date: 2026-01-23
venue: L4DC
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2511.19383.pdf'
arxivurl: 'https://arxiv.org/abs/2511.19383'
githuburl: 'https://github.com/mlab-upenn/L2O-MIQP'
bibtexurl: #'http://academicpages.github.io/files/bibtex1.bib'
citation: # 1
---
<!-- The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font. -->

This work proposes a learning-to-optimize (L2O) framework for accelerating the solution of parametric MIQP problems by learning structured solution components directly from data. The key idea is to predict high-quality integer decisions using a neural network, while preserving exact continuous optimality by solving a differentiable quadratic programming (QP) layer conditioned on the predicted integers. By explicitly separating discrete and continuous variables, the framework leverages problem structure and improves both feasibility and performance.

To train the model, we introduce a hybrid loss function that combines:

- a supervised loss, encouraging predicted integer solutions to match globally optimal ones when labels are available, and
- a self-supervised loss, derived directly from the MIQP objective and constraints, promoting feasibility and consistency even without labeled solutions.

This hybrid learning strategy bridges the gap between purely supervised and purely self-supervised approaches. The effectiveness of the proposed method is demonstrated on benchmark MI-MPC problems, where it achieves significant computational speedups while maintaining strong feasibility and near-optimal control performance.

- **Paper**: https://arxiv.org/abs/2511.19383
- **GitHub Repository**: https://github.com/mlab-upenn/L2O-MIQP
- **BibTeX**:
```bibtex
@inproceedings{le2026hybrid,
  title={{A Hybrid Learning-to-Optimize Framework for Mixed-Integer Quadratic Programming}}, 
  author={Le, Viet-Anh and Xie, Mu and Mangharam, Rahul},
  year={2026},
  booktitle={8th Annual Learning for Dynamics \& Control Conference},
}
```
