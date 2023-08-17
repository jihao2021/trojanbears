---
layout: paper
title: "GAN-DUF: Hierarchical Deep Generative Models for Design Under Free-Form Geometric Uncertainty"
year: "2022"
shortref: "Chen et al. <i>JMD</i> 2022"
nickname: chen2022gandufjmd
journal: "Journal of Mechanical Design"
volume: 145
issue: 1
pages: 011703
authors: "Wei (Wayne) Chen, Doksoo Lee, Oluwaseyi Balogun, and Wei Chen"
image: /assets/images/papers/2022_ganduf_jmd.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/md_145_1_011703.pdf
pdflink: 
github: 'https://github.com/wchen459/GAN-DUF'
doi: 10.1115/1.4055898
category: paper
published: true
tags: [ganduf_jmd]
---
{% include JB/setup %}

# Abstract 

Deep generative models have demonstrated effectiveness in learning compact and expressive design representations that significantly improve geometric design optimization. However, these models do not consider the uncertainty introduced by manufacturing or fabrication. The past work that quantifies such uncertainty often makes simplifying assumptions on geometric variations, while the “real-world,” “free-form” uncertainty and its impact on design performance are difficult to quantify due to the high dimensionality. To address this issue, we propose a generative adversarial network-based design under uncertainty framework (GAN-DUF), which contains a deep generative model that simultaneously learns a compact representation of nominal (ideal) designs and the conditional distribution of fabricated designs given any nominal design. This opens up new possibilities of (1) building a universal uncertainty quantification model compatible with both shape and topological designs, (2) modeling free-form geometric uncertainties without the need to make any assumptions on the distribution of geometric variability, and (3) allowing fast prediction of uncertainties for new nominal designs. We can combine the proposed deep generative model with robust design optimization or reliability-based design optimization for design under uncertainty. We demonstrated the framework on two real-world engineering design examples and showed its capability of finding the solution that possesses better performance after fabrication.




# BibTeX Citation

```
@article{10.1115/1.4055898,
    author = {Chen, Wei (Wayne) and Lee, Doksoo and Balogun, Oluwaseyi and Chen, Wei},
    title = "{GAN-DUF: Hierarchical Deep Generative Models for Design Under Free-Form Geometric Uncertainty}",
    journal = {Journal of Mechanical Design},
    volume = {145},
    number = {1},
    pages = {011703},
    year = {2022},
    month = {10},
    issn = {1050-0472},
    doi = {10.1115/1.4055898},
    url = {https://doi.org/10.1115/1.4055898},
    eprint = {https://asmedigitalcollection.asme.org/mechanicaldesign/article-pdf/145/1/011703/6934016/md\_145\_1\_011703.pdf},
}
```
