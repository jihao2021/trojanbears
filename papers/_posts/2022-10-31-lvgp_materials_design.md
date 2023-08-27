---
layout: paper
title: "Uncertainty-Aware Mixed-Variable Machine Learning for Materials Design"
year: "2022"
shortref: "Zhang et al. <i>Sci. Rep.</i> 2022"
nickname: zhang2022lvgp
journal: "Scientific Reports"
volume: 12
issue: 
pages: 19760
authors: "Hengrui Zhang, Wei (Wayne) Chen, Akshay Iyer, Daniel W. Apley, and Wei Chen"
image: /assets/images/papers/2022_lvgp.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2207.04994.pdf
pdflink: 
github: 
doi: 10.1038/s41598-022-23431-2
category: paper
published: true
tags: [journal]
---
{% include JB/setup %}

# Abstract 

Data-driven design shows the promise of accelerating materials discovery but is challenging due to the prohibitive cost of searching the vast design space of chemistry, structure, and synthesis methods. Bayesian optimization (BO) employs uncertainty-aware machine learning models to select promising designs to evaluate, hence reducing the cost. However, BO with mixed numerical and categorical variables, which is of particular interest in materials design, has not been well studied. In this work, we survey frequentist and Bayesian approaches to uncertainty quantification of machine learning with mixed variables. We then conduct a systematic comparative study of their performances in BO using a popular representative model from each group, the random forest-based Lolo model (frequentist) and the latent variable Gaussian process model (Bayesian). We examine the efficacy of the two models in the optimization of mathematical functions, as well as properties of structural and functional materials, where we observe performance differences as related to problem dimensionality and complexity. By investigating the machine learning models’ predictive and uncertainty estimation capabilities, we provide interpretations of the observed performance differences. Our results provide practical guidance on choosing between frequentist and Bayesian uncertainty-aware machine learning models for mixed-variable BO in materials design.




# BibTeX Citation

```
@article{zhang2022uncertainty,
  title={Uncertainty-aware mixed-variable machine learning for materials design},
  author={Zhang, Hengrui and Chen, Wei and Iyer, Akshay and Apley, Daniel W and Chen, Wei},
  journal={Scientific Reports},
  volume={12},
  number={1},
  pages={19760},
  year={2022},
  publisher={Nature Publishing Group UK London}
}
```
