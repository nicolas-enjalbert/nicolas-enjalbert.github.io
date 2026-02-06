---
layout: page
title: "Biostatistics analysis of RNA-Seq data"
nav: false
---


This course is part of the INRAE training session about “bioinformatics and biostatistics analysis of RNA-seq data” and proposed in collaboration with the [Biostatistics platform](https://genotoul-biostat.pages-forge.inrae.fr/website/). The previous sessions were held in Toulouse on November 18-21, 2014, April 2-3, 2015, September 23-24, 2015, May 18-19, 2017, February 11-12, 2019, November 4-5, 2020, April 14-15, 2021, April 13-14, 2022, March 29-30, 2023,  May 16-17, 2024, and November 26-27, 2025. The next session is scheduled on April 01-02, 2026.

The material provided on the present webpage is related to the biostatistics part and covers the following topics:

- R and RStudio
- design of experiments
- variability
- count data normalization
- differential analysis

_The material has originally been prepared by Ignacio Gonzales, Annick Moisan and **Nathalie Vialaneix**. The class has already been taught by these persons but also by Gaëlle Lefort, Jérôme Mariette, Philippe Bordron, Fabien Grazani and Nicolas Enjalbert-Courrech._

**Pre-requisites**: A background in **R** programming is necessary for this class. Before the class, please download the course material and install R, RStudio and the packages as described below. To produce high quality figures, I will use `ggplot2` for plots but will not enter into details about the `ggplot2` syntax. If you are not familiar with it, you can just use these command lines or switch to base plots instead. Do not hesitate to contact me before the class if you have any difficulty to install one of these packages!

## Material 

- [(theoretical part) slides](https://formations-statistique.pages-forge.inrae.fr/rnaseq/slides_lesson.pdf)
practical application: [material](https://www.nathalievialaneix.eu/doc/zip/material-rnaseq.zip), including a subdirectory data (with datasets) and an Rmd (source) file. This file can be compiled within RStudio and will provide an [HTML file of the complete analysis](https://www.nathalievialaneix.eu/doc/html/edgeR-RNAseq.html).

## Required installation for the pratical application

**R** is needed for the pratical application and Rstudio is strongly advised. Id possible, use **R** version 1.0 or higher. detailled installation instributions are provided on this page. 

**Packages**: 

- ggplot2
- gridExtra
- reshape2
- RColorBrewer
- VennDiagram
- plotly
- mixOmics
- edgeR

These packages can be installed using the package `pak` 
```
install.packages("pak")
pak::pak(c("ggplot2", "gridEtra", "reshape2", "RColorBrewer", "VennDiagram", "plotly", "mixOmcis", "edgeR"))
```

The package `pak` allows the installation from CRAN et Bioconductor sources. 


--------
This page is inspired/taken from [Nathalie Vialaneix's web](https://www.nathalievialaneix.eu/teaching/rnaseq.html)
