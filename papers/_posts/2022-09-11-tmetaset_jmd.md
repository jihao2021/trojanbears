---
layout: paper
title: "t-METASET: Tailoring Property Bias of Large-Scale Metamaterial Datasets through Active Learning"
year: "2022"
shortref: "Lee et al. <i>JMD</i> 2022"
nickname: lee2022tmetasetjmd
journal: "Journal of Mechanical Design"
volume: 145
issue: 3
pages: 031704
authors: "Doksoo Lee, Yu-Chin Chan, Wei (Wayne) Chen, Liwei Wang, Anton van Beek, and Wei Chen"
image: /assets/images/papers/2022_tmetaset_jmd.png
redirect_from: 
fulltext: 
pdf: /assets/pdfs/2202.10565.pdf
pdflink: 
github: 
doi: 10.1115/1.4055925
category: paper
published: true
tags: [tmetaset_jmd]
---
{% include JB/setup %}

# Abstract 

Inspired by the recent achievements of machine learning in diverse domains, data-driven metamaterials design has emerged as a compelling paradigm that can unlock the potential of multiscale architectures. The model-centric research trend, however, lacks principled frameworks dedicated to data acquisition, whose quality propagates into the downstream tasks. Often built by naive space-filling design in shape descriptor space, metamaterial datasets suffer from property distributions that are either highly imbalanced or at odds with design tasks of interest. To this end, we present t-METASET: an active learning-based data acquisition framework aiming to guide both diverse and task-aware data generation. Distinctly, we seek a solution to a commonplace yet frequently overlooked scenario at early stages of data-driven design of metamaterials: when a massive (∼O(104)) shape-only library has been prepared with no properties evaluated. The key idea is to harness a data-driven shape descriptor learned from generative models, fit a sparse regressor as a start-up agent, and leverage metrics related to diversity to drive data acquisition to areas that help designers fulfill design goals. We validate the proposed framework in three deployment cases, which encompass general use, task-specific use, and tailorable use. Two large-scale mechanical metamaterial datasets are used to demonstrate the efficacy. Applicable to general image-based design representations, t-METASET could boost future advancements in data-driven design.




# BibTeX Citation

```
@article{10.1115/1.4055925,
    author = {Lee, Doksoo and Chan, Yu-Chin and Chen, Wei (Wayne) and Wang, Liwei and van Beek, Anton and Chen, Wei},
    title = "{t-METASET: Task-Aware Acquisition of Metamaterial Datasets Through Diversity-Based Active Learning}",
    journal = {Journal of Mechanical Design},
    volume = {145},
    number = {3},
    pages = {031704},
    year = {2022},
    month = {11},
    issn = {1050-0472},
    doi = {10.1115/1.4055925},
    url = {https://doi.org/10.1115/1.4055925},
    eprint = {https://asmedigitalcollection.asme.org/mechanicaldesign/article-pdf/145/3/031704/6938884/md\_145\_3\_031704.pdf},
}
```
