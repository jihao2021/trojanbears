---
layout: paper
title: "Range-GAN: Range-Constrained Generative Adversarial Network for Conditioned Design Synthesis"
year: "2021"
shortref: "Nobari et al. <i>ASME IDETC</i> 2021"
nickname: nobari2021rangeganidetc
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Amin Heyrani Nobari, Wei Chen, and Faez Ahmed"
image: /assets/images/papers/2021_rangegan_idetc.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2103.06230.pdf
pdflink: 
github: "https://github.com/ahnobari/Range-GAN"
doi: 10.1115/DETC2021-69963
category: paper
published: true
tags: [rangegan]
---
{% include JB/setup %}

# Abstract 

Typical engineering design tasks require the effort to modify designs iteratively until they meet certain constraints, i.e., performance or attribute requirements. Past work has proposed ways to solve the inverse design problem, where desired designs are directly generated from specified requirements, thus avoid the trial and error process. Among those approaches, the conditional deep generative model shows great potential since 1) it works for complex high-dimensional designs and 2) it can generate multiple alternative designs given any condition. In this work, we propose a conditional deep generative model, Range-GAN, to achieve automatic design synthesis subject to range constraints. The proposed model addresses the sparse conditioning issue in data-driven inverse design problems by introducing a label-aware self-augmentation approach. We also propose a new uniformity loss to ensure generated designs evenly cover the given requirement range. Through a real-world example of constrained 3D shape generation, we show that the label-aware self-augmentation leads to an average improvement of 14% on the constraint satisfaction for generated 3D shapes, and the uniformity loss leads to a 125% average increase on the uniformity of generated shapes’ attributes. This work laid the foundation for data-driven inverse design problems where we consider range constraints and there are sparse regions in the condition space. For further information and code for this paper please refer to http://decode.mit.edu/projects/rangegan/.



# BibTeX Citation

```
@proceedings{10.1115/DETC2021-69963,
    author = {Heyrani Nobari, Amin and Chen, Wei and Ahmed, Faez},
    title = "{Range-GAN: Range-Constrained Generative Adversarial Network for Conditioned Design Synthesis}",
    volume = {Volume 3B: 47th Design Automation Conference (DAC)},
    series = {International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
    pages = {V03BT03A039},
    year = {2021},
    month = {08},
    doi = {10.1115/DETC2021-69963},
    url = {https://doi.org/10.1115/DETC2021-69963},
    eprint = {https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-pdf/IDETC-CIE2021/85390/V03BT03A039/6801531/v03bt03a039-detc2021-69963.pdf},
}

```
