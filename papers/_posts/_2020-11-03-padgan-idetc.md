---
layout: paper
title: "PaDGAN: A Generative Adversarial Network for Performance Augmented Diverse Designs"
year: "2020"
shortref: "Chen and Ahmed <i>ASME IDETC</i> 2020"
nickname: chen2020padganidetc
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Wei Chen and Faez Ahmed"
image: /assets/images/papers/2020_padgan_idetc.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2002.11304.pdf
pdflink: 
github: "https://github.com/wchen459/PaDGAN"
doi:
category: paper
published: true
tags: [padgan]
---
{% include JB/setup %}

# Abstract 

Deep generative models are proven to be a useful tool for automatic design synthesis and design space exploration. When applied in engineering design, existing generative models face three challenges: 1) generated designs lack diversity and do not cover all areas of the design space, 2) it is difficult to explicitly improve the overall performance or quality of generated designs, and 3) existing models generate do not generate novel designs, outside the domain of the training data. In this paper, we simultaneously address these challenges by proposing a new Determinantal Point Processes based loss function for probabilistic modeling of diversity and quality. With this new loss function, we develop a variant of the Generative Adversarial Network, named “Performance Augmented Diverse Generative Adversarial Network” or PaDGAN, which can generate novel high-quality designs with good coverage of the design space. Using three synthetic examples and one real-world airfoil design example, we demonstrate that PaDGAN can generate diverse and high-quality designs. In comparison to a vanilla Generative Adversarial Network, on average, it generates samples with 28% higher mean quality score with larger diversity and without the mode collapse issue. Unlike typical generative models that usually generate new designs by interpolating within the boundary of training data, we show that PaDGAN expands the design space boundary outside the training data towards high-quality regions. The proposed method is broadly applicable to many tasks including design space exploration, design optimization, and creative solution recommendation.



# BibTeX Citation

```
@proceedings{10.1115/DETC2020-22729,
    author = {Chen, Wei and Ahmed, Faez},
    title = "{PaDGAN: A Generative Adversarial Network for Performance Augmented Diverse Designs}",
    volume = {Volume 11A: 46th Design Automation Conference (DAC)},
    series = {International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
    pages = {V11AT11A010},
    year = {2020},
    month = {08},
    doi = {10.1115/DETC2020-22729},
    url = {https://doi.org/10.1115/DETC2020-22729},
    eprint = {https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-pdf/IDETC-CIE2020/84003/V11AT11A010/6587039/v11at11a010-detc2020-22729.pdf},
}
```
