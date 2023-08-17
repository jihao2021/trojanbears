---
layout: paper
title: "t-METASET: Tailoring Property Bias of Large-Scale Metamaterial Datasets through Active Learning"
year: "2022"
shortref: "Lee et al. <i>ASME IDETC</i> 2022"
nickname: lee2022tmetaset
journal: "Proceedings of the ASME International Design Engineering Technical Conferences"
volume: 
issue: 
pages: 
authors: "Doksoo Lee, Yu-Chin Chan, Wei (Wayne) Chen, Liwei Wang, Anton van Beek, and Wei Chen"
image: /assets/images/papers/2022_tmetaset_idetc.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2202.10565.pdf
pdflink: 
github:
doi: 10.1115/DETC2022-87653
category: paper
published: true
tags: [tmetaset_idetc]
---
{% include JB/setup %}

# Abstract 

Inspired by the recent achievements of machine learning in diverse domains, data-driven metamaterials design has emerged as a compelling paradigm that can unlock the potential of the multiscale architectures. The model-centric research trend, however, lacks principled frameworks dedicated to data acquisition, whose quality propagates into the downstream tasks. Built by naive space-filling design in shape descriptor space, metamaterial datasets suffer from property distributions that are either highly imbalanced or at odds with design tasks of interest. To this end, we present t-METASET: an active-learning-based data acquisition framework aiming to guide both balanced and task-aware data generation. Uniquely, we seek a solution to a commonplace yet frequently overlooked scenario at early stages of data-driven design: when a massive shape-only library has been prepared with no properties evaluated. The key idea is to harness a data-driven shape descriptor learned from generative models, fit a sparse regressor as a start-up agent, and leverage metrics related to diversity to drive data acquisition to areas that help designers fulfill design goals. We validate the proposed framework in three deployment cases, which encompass general use, task-specific use, and tailorable use. Two large-scale mechanical metamaterial datasets (∼ O(104)) are used to demonstrate the efficacy. Applicable to general design representations, t-METASET can boost future advancements in data-driven design.



# BibTeX Citation

```
@proceedings{10.1115/DETC2022-87653,
    author = {Lee, Doksoo and Chan, Yu-Chin and Chen, Wei (Wayne) and Wang, Liwei and Chen, Wei},
    title = "{t-METASET: Task-Aware Generation of Metamaterial Datasets by Diversity-Based Active Learning}",
    volume = {Volume 3A: 48th Design Automation Conference (DAC)},
    series = {International Design Engineering Technical Conferences and Computers and Information in Engineering Conference},
    pages = {V03AT03A011},
    year = {2022},
    month = {08},
    doi = {10.1115/DETC2022-87653},
    url = {https://doi.org/10.1115/DETC2022-87653},
    eprint = {https://asmedigitalcollection.asme.org/IDETC-CIE/proceedings-pdf/IDETC-CIE2022/86229/V03AT03A011/6942978/v03at03a011-detc2022-87653.pdf},
}
```
