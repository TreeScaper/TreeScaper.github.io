---
permalink: /
title: "CloudForest"
author_profile: false
sidebar:
    - image: "/assets/images/tree-network-cartoon.png"
    - title: "Quick Links"
      text: [Getting Started](https://btoup15.github.io/getting%20started/CRA-tutorial/)
---

# What is CloudForest?

CloudForest is a portable, easy-to-deploy, and reproducible computational platform for phylogenomics. The goal of CloudForest is to serve as a bridge that allows researchers to span all steps of a phylogenomic analysis, in order to explore and better understand variation and structure in sets of phylogenetic trees. While the tools available in CloudForest have many applications, some use cases include:

- Comparing the results of different phylogenomic analyses
- Exploring gene tree variation
- Identifying outlier genes
- Identifying species of hybrid origin
- Community phylogenetics and biogeography
- Sensitivity analyses (particularly for Bayesian inference)


# Architecture

CloudForest is built on the [Galaxy](https://galaxyproject.org) platform, which allows it to integrate seamlessly with various tools for phylogenetic inference and visualization. CloudForest runs inside a self-contained, customized [Docker](https://www.docker.com) image, making it easily portable to different operating systems and computing architectures. To reduce local computing burden, CloudForest can automatically offload analyses to publicly available computing clusters (e.g., [CIPRES](https://www.phylo.org)) and download results for further analysis. 


# Relationship to TreeScaper

We previously developed TreeScaper ([Huang et al., 2016](https://doi.org/10.1093/molbev/msw196)), which plays a critical role in CloudForest workflows. TreeScaper is used to create low-dimensional visualizations of tree space, estimate the intrinsic dimensionality of a tree set, construct tree- and bipartition-based networks, and perform community detection on these networks. As input, TreeScaper accepts any set of phylogenetic trees created by a wide variety of phylogenetic inference programs. Data structures and results from TreeScaper analyses can be visualized in a variety of ways in CloudForest.


# What to Cite

Wagner R, Toups BS, Deng Z, Gallivan KA, Brown JM, Wilgenbusch JC. 2021. [Investigating the genomic distribution of phylogenetic signal with CloudForest.](https://doi.org/10.1145/3437359.3465605) In *Practice and Experience in Advanced Research Computing (PEARC '21)*, July 18–22, 2021, Boston, MA, USA. ACM, New York, NY, USA, 4 pages. [**Please cite for use of CloudForest.**]

Huang W, Zhou G, Marchand M, Ash JR, Morris D, Van Dooren P, Brown JM, Gallivan KA, Wilgenbusch JC. 2016. [TreeScaper: visualizing and extracting phylogenetic signal from sets of trees.](https://doi.org/10.1093/molbev/msw196) *Molecular Biology and Evolution*. 33:3314-3316. [**Please cite for direct use of TreeScaper, or any analyses involving NLDR or community detection.**]

Wilgenbusch JC, Huang W, Gallivan KA. 2017. [Visualizing phylogenetic tree landscapes.](https://link.springer.com/article/10.1186/s12859-017-1479-1) *BMC Bioinformatics*. 18:85. [**Please cite for analyses involving NLDR visualizations of tree space.**]

Brown JM, Mount GG, Gallivan KA, Wilgenbusch JC. 2021. [The diverse applications of tree set visualization and exploration.](https://ecoevorxiv.org/2d6ph/) In *Estimating Species Trees: Practical and Theoretical Aspects, 2nd edition.* Eds. L. Knowles and L. Kubatko. In Press. [**Please cite as general overview and potential applications of TreeScaper and CloudForest.**]


# Funding

The development of TreeScaper and CloudForest have been supported by grants from the National Science Foundation to J.C. Wilgenbusch (DBI-1262476 and DBI-1934182), K.A. Gallivan (DBI-1262476 and DBI-1934157), and J.M. Brown (DBI-1262571 and DBI-1934156).

![NSF Logo](https://raw.githubusercontent.com/jembrown/TreeScaper.github.io/master/assets/images/nsfLogo.png)
