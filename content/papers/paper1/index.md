---
title: "Structured nonnegative matrix factorization for traffic flow estimation of large cloud networks" 
date: 2021-24-12
tags: ["traffic matrix","inverse problem","routing matrix", "nonnegativity", "autoregression", "orthogonality", "training algorithm"]
author: "Syed Muhammad Atif, Nicolas Gillis, Sameer Qazi, Imran Naseem"
description: "In this paper, we propose a novel model for the network traffic matrix estimation problem which maps high-dimension OD flows to low-dimension latent flows with the following three constraints: (1) nonnegativity constraint on the estimated OD flows, (2) autoregression constraint that enables the proposed model to effectively capture temporal patterns of the OD flows, and (3) orthogonality constraint that ensures the mapping between low-dimensional latent flows and the corresponding link flows to be distance preserving. The parameters of the proposed model are estimated with a training algorithm based on Nesterov accelerated gradient and generally shows fast convergence." 
summary: "In this paper, we propose a novel model for the network traffic matrix estimation problem which maps high-dimension OD flows to low-dimension latent flows with the following three constraints: (1) nonnegativity constraint on the estimated OD flows, (2) autoregression constraint that enables the proposed model to effectively capture temporal patterns of the OD flows, and (3) orthogonality constraint that ensures the mapping between low-dimensional latent flows and the corresponding link flows to be distance preserving. The parameters of the proposed model are estimated with a training algorithm based on Nesterov accelerated gradient and generally shows fast convergence." 
cover:
    image: "paper1.png"
    alt: "Image caption"
    relative: false
editPost:
    URL: "https://doi.org/10.1016/j.comnet.2021.108564"
    Text: "Computer Networks"

---

---

##### Download

+ [Paper](paper1.pdf)
+ [Online appendix](appendix1.pdf)
+ [Code and data](https://github.com/pmichaillat/job-rationing)

---

##### Abstract

Network traffic matrix estimation is an ill-posed linear inverse problem: it requires to estimate the unobservable origin destination traffic flows, X, given the observable link traffic flows, Y, and a binary routing matrix, A, which are such that Y = AX. This is a challenging but vital problem as accurate estimation of OD flows is required for several network management tasks. In this paper, we propose a novel model for the network traffic matrix estimation problem which maps high-dimension OD flows to low-dimension latent flows with the following three constraints: (1) nonnegativity constraint on the estimated OD flows, (2) autoregression constraint that enables the proposed model to effectively capture temporal patterns of the OD flows, and (3) orthogonality constraint that ensures the mapping between low-dimensional latent flows and the corresponding link flows to be distance preserving. The parameters of the proposed model are estimated with a training algorithm based on Nesterov accelerated gradient and generally shows fast convergence. We validate the proposed traffic flow estimation model on two real backbone IP network datasets, namely Internet2 and GÉANT. Empirical results show that the proposed model outperforms the state-of-the-art models not only in terms of tracking the individual OD flows but also in terms of standard performance metrics. The proposed model is also found to be highly scalable compared to the existing state-of-the-art approaches.

---

##### Figure X: Figure caption

![](paper1.png)

---

##### Citation

Author. Year. "Title." *Journal* Volume (Issue): First page–Last page. https://doi.org/paper_doi.

```BibTeX
@article{AAYY,
author = {Author},
doi = {paper_doi},
journal = {Journal},
number = {Issue},
pages = {XXX--YYY},
title ={Title},
volume = {Volume},
year = {Year}}
```

---

##### Related material

+ [Presentation slides](presentation1.pdf)
+ [Dissertation title](https://escholarship.org/uc/item/7jr3m96r) – PhD dissertation on which this paper is based.
+ [Column title](https://cep.lse.ac.uk/pubs/download/cp365.pdf) – Nontechnical column describing the paper.

