# Olympia-Oyster-Gene-Expression
This repository contains R code used for the analyses of gene expression described in Maynard et al. (2018) Transcriptomic responses to extreme low salinity among locally adapted populations of Olympia oyster (Ostrea lurida).
Analysis used the DeSeq2 package in R to determine differences in gene expression among three populations of oyster exposed to extreme low salinity.
The DESeq2 protocol requires a matrix of raw counts and a bioconidtions file as outlined in the DESeq2 vignette.
Code includes general linear models for single factors as well as an interaction term
Also includes code for performing principal components analysis.
Based on code described in the DESeq2 manual:
https://bioconductor.org/packages/release/bioc/manuals/DESeq2/man/DESeq2.pdf
