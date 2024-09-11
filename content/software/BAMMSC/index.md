---
date: 2020-08-18
description: ""
#featured_image: "/images/Pope-Edouard-de-Beaumont-1844.jpg"
#tags: ["scene"]
title: "BAMMSC"
summary: "An R package for clustering droplet-based single cell RNA-seq data from multiple individuals simultaneously, capable of correcting for certain data heterogenity and batch effect across samples"
weight: 19
---

BAMMSC is an R package for clustering droplet-based single cell transcriptomic data from multiple individuals simultaneously. It adopts a Bayesian hierarchical Dirichlet multinomial mixture model, which explicitly characterizes three levels of variabilities (i.e., genes, cell types and individuals). BAMMSC is able to taking account for data heterogeneity and batch effect, such as unbalanced sequencing depths, variable read length and hidden technical bias, among multiple individuals. BAMMSC also integrates DIMMSC for single individual analysis. The BAMMSC codebase and examples is currently available [here](https://github.com/lichen-lab/BAMMSC).

**Reference**

Sun, Zhe & Chen, Li & Xin, Hongyi & Huang, Qianhui & Cillo, Anthony & Tabib, Tracy & Ding, Ying & Kolls, Jay & Bruno, Tullia & Lafyatis, Robert & Vignali, Dario & Chen, Kong & Hu, Ming & Chen, Wei. [A Bayesian mixture model for clustering droplet-based single-cell transcriptomic data from population studies](https://pubmed.ncbi.nlm.nih.gov/30967541/). Nat Commun. 2019;10(1):1649. Published 2019 Apr 9. doi:10.1038/s41467-019-09639-3
