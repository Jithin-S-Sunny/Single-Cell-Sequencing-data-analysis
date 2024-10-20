# Single-cell data analysis

# Data
This single-cell study corresponds to Peripheral Blood Mononuclear Cell (PBMC) single-cell RNA-seq (scRNA-seq) data from the manuscript. In particular, this study contains data from 6 scRNA-seq methods (Smart-seq2, CEL-Seq2, 10x Chromium, Drop-seq, Seq-Well, and inDrops). Each method was applied to two replicates (PBMC1 and PBMC2).
https://www.biorxiv.org/content/10.1101/632216v2

The portal contains log normalized UMI counts per 10,000 data from all these methods, except for Smart-seq2 with log normalized read counts per 10,000 data.

# Introduction
PBMC is composed of various specialized immune cells such as lymphocytes, monocytes and dendritic cells. PBMCs contain different multipotent cells that can differentiate into blood cells, endothelial cells, hepatocytes, smooth muscle cells, osteoblasts amongst others. In isolated PBMCs, T cells amount to 45–70% of the total cells making it by far the most abundant cell type. 

Analysis based on Single Cell Portal (SCP) server
A non-linear dimensionality reduction algorithm called tSNE is applied here which produces clusters from high dimensional, almost indistinct expression data. The probability of similarity amongst points is converted to a low dimensional space using the conditional probabilities of two probabilities say Pxy and Pjy at high dimension. Under the assumption of t-distribution, similar points are deduced
The 12 clusters defined in Fig 1, show the relative closeness of each cell. On the right shows the clusters based on cell types. CD4+ T cells can be seen in blue in the top right quadrant.    


