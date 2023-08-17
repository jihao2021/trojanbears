---
layout: paper
title: "Hierarchical Deep Generative Models for Design Under Free-Form Geometric Uncertainty"
year: "2022"
shortref: "Chen et al. <i>ASME IDETC</i> 2022"
nickname: chen2022ganduf
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Wei (Wayne) Chen, Doksoo Lee, Oluwaseyi Balogun, and Wei Chen"
image: /assets/images/papers/2022_ganduf_idetc.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/GAN_DUF__Hierarchical_Deep_Generative_Models_for_Design_Under_Free_Form_Geometric_Uncertainty.pdf
pdflink: 
github: 'https://github.com/wchen459/GAN-DUF'
doi: 10.1115/DETC2022-89707
category: paper
published: true
tags: [ganduf_idetc]
---
{% include JB/setup %}

# Abstract 

Deep generative models have demonstrated effectiveness in learning compact and expressive design representations that significantly improve geometric design optimization. However, these models do not consider the uncertainty introduced by manufacturing or fabrication. Past work that quantifies such uncertainty often makes simplifying assumptions on geometric variations, while the “real-world”, “free-form” uncertainty and its impact on design performance are difficult to quantify due to the high dimensionality. To address this issue, we propose a Generative Adversarial Network-based Design under Uncertainty Framework (GAN-DUF), which contains a deep generative model that simultaneously learns a compact representation of nominal (ideal) designs and the conditional distribution of fabricated designs given any nominal design. This opens up new possibilities of 1) building a universal uncertainty quantification model compatible with both shape and topological designs, 2) modeling free-form geometric uncertainties without the need to make any assumptions on the distribution of geometric variability, and 3) allowing fast prediction of uncertainties for new nominal designs. We can combine the proposed deep generative model with robust design optimization or reliability-based design optimization for design under uncertainty. We demonstrated the framework on two real-world engineering design examples and showed its capability of finding the solution that possesses better performances after fabrication.



# BibTeX Citation

```
@proceedings{10.1115/DETC2022-89707,
    author = {Chen, Wei (Wayne) and Lee, Doksoo and Balogun, Oluwaseyi and Chen, Wei},
    title = "{Hierarchical Deep Generative Models for Design Under Free-Form Geometric Uncertainty}",
    volume = {Volume 3B: 48th Design Automation Conference (DAC)},
    series = {International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
    pages = {V03BT03A042},
    year = {2022},
    month = {08},
    doi = {10.1115/DETC2022-89707},
    url = {https://doi.org/10.1115/DETC2022-89707},
    eprint = {https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-pdf/IDETC-CIE2022/86236/V03BT03A042/6943285/v03bt03a042-detc2022-89707.pdf},
}
```
