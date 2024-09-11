---
title: Research

# View.
#   1 = List
#   2 = Compact
#   3 = Card
view: 2

# Optional header image (relative to `static/media/` folder).
#header:
#  caption: ""
#  image: "research.jpg"
toc: true
---
{{< figure library="true" src="research.jpg" >}}

Below is a summary of major active research projects.

## **A. Statistical and computational methods for single cell multi-omics data**

The study of single cell transcriptome can shed light on cellular and molecular processes at single cell resolution, which is essential for understanding the heterogeneity of cell populations across different conditions. The recently developed droplet-based single cell transcriptome sequencing (scRNA-seq) technology and its extension, such as 10X Genomics Chromium system, is able to measure the gene expression and other type of data in tens of thousands of single cells from multiple individuals simultaneously in a short time period and at relatively low cost, making a population-scale single cell transcriptome study feasible. Despite the progress of method developments for analyzing scRNA-seq data from early generation platforms, there is a severe lack of tailored statistical methods and efficient computational tools for analyzing scRNA-seq data increased by an order of magnitude from this new generation platform. Our group is in the first place at the University of Pittsburgh to study single cell transcriptomic profiling using the new droplet-based platform (10X Genomics). Collaborating with world-class experts at UPMC and Pitt, we have generated high-quality scRNA data (thousands of cells per sample) to study human diseases. We are also actively developing novel computational methods to facilitate our ongoing analysis and address new challenges. 

Major publications: 

+ Sun Z, Wang T, Deng K, Wang XF, Lafyatis R, Ding Y, Hu M, **Chen W**. DIMM-SC: a Dirichlet mixture model for clustering droplet-based single cell transcriptomic data. <ins><em>Bioinformatics (Oxford, England). 2018;34(1):139-46.</em></ins>

+ Sun Z, Chen L, Xin H, Jiang Y, Huang Q, Cillo AR, Tabib T, Kolls JK, Bruno TC, Lafyatis R, Vignali DAA, Chen K, Ding Y, Hu M, **Chen W**. A Bayesian mixture model for clustering droplet-based single-cell transcriptomic data from population studies. <em><ins>Nature Communications. 2019;10(1):1649.</ins></em>

+ Wang X, Sun Z, Zhang Y, Xu Z, Xin H, Huang H, Duerr RH, Chen K, Ding Y, **Chen W**. BREM-SC: a bayesian random effects mixture model for joint clustering single cell multi-omics data. <em><ins>Nucleic Acids Research. 2020.</ins></em>

+ Xin H, Yan Q, Jiang Y, Lian Q, Wang X, Luo J, Erb C, Duerr R, Chen K, **Chen W**. Sample demultiplexing, multiplet detection, experiment planning and novel cell type verification in single cell sequencing. <em><ins>Genome Biology. 21, Article number: 188 (2020).</ins></em>

## **B. Statistical methods for high-dimensional genomics data**

Motivated by the challenges from the analysis of multi-omics data such as RNA-seq, methylation, and ATAC-seq, we are developing novel statistical methods to understand the association between different type of data and their relation with clinical outcomes.

Major publications: 

+ Ding Y, Kong S, Kang S, **Chen W**. A semiparametric imputation approach for regression with censored covariate with application to an AMD progression study. <em><ins>Statistics in Medicine. 2018;37(23):3293-308.</ins></em>

+ Wei Y, Liu Y, Sun T, **Chen W**, Ding Y. Gene-based association analysis for bivariate time-to-event data through functional regression with copula models. <em><ins>Biometrics. 2020 Jun;76(2):619-629. doi: 10.1111/biom.13165. Epub 2019 Nov 14.</ins></em>

+ Wang T, Ren Z, Ding Y, Fang Z, Sun Z, MacDonald ML, Sweet RA, Wang J, **Chen W**<sup>#</sup>. FastGGM: An Efficient Algorithm for the Inference of Gaussian Graphical Model in Biological Networks. <em><ins>PLoS Computational Biology. 2016;12(2):e1004755.</ins></em>

+ Zhang R, Ren Z, **Chen W**. SILGGM: An extensive R package for efficient statistical inference in large-scale gene networks. <em><ins>PLoS Computational Biology. 2018;14(8):e1006369.</ins></em>

+ Zhang R, Ren Z, Celedón JC, **Chen W**. (2020)    Inference of Large Modified Poisson-type Graphical Models: Application to RNA-seq Data in Childhood Atopic Asthma Studies. <em><ins>Annals of Applied Statistics. In Press.</ins></em>

+ Sun T, Wei Y, **Chen W**, Ding Y. GWAS-based Deep Learning for Survival Prediction. 2020. In Press. <em><ins>Statistics in Medicine.</ins></em>


## **C. AMD Genetics and Disease Prediction**

Genome-wide association study (GWAS) has led to notable successes in identifying multiple loci associated with the risk of age-related macular degeneration (AMD). Disease risk loci have been identified through GWAS, either by individual studies or through meta-analyses of multiple studies from Consortium. On the other hand, there are growing interests on disease progression (e.g. time to advanced AMD). Genome-wide survey on survival or longitudinal type of data has not been formulated and well performed in the area of AMD. Genes that affect AMD progression are largely unknown. Emerging genetic and phenotypic data from our collaborators provide unique opportunity for us to develop statistical methods on existing data sets and facilitate ongoing consortium studies in which we are involved. In addition, synergy of genome-wide genetic data, fundus imaging data and progression outcomes will greatly advance our knowledge about disease biology and its prediction. We are developing statistical and machine learning method to analyze large-scale fundus imaging and genetic data to understand the dynamic change of AMD. 

Recent major publications: 

+ **Chen W**, Stambolian D, Edwards AO, … , Haines JL, Gorin MB, Abecasis GR, Swaroop A. Genetic variants near TIMP3 and high-density lipoprotein-associated loci influence susceptibility to age-related macular degeneration. <em><ins>Proceedings of the National Academy of Sciences of the United States of America. 2010;107(16):7401-6.</ins></em>

+ Fritsche LG\*, **Chen W**\*, Schu M, … , Farrer LA, Heid IM, Abecasis GR, Consortium AMDG. Seven new loci associated with age-related macular degeneration. <em><ins>Nature Genetics. 2013;45(4):433-9, 9e1-2.</ins></em>

+ Ding Y, Liu Y, Yan Q, Fritsche LG, Cook RJ, Clemons T, Ratnapriya R, Klein ML, Abecasis GR, Swaroop A, Chew EY, Weeks DE, **Chen W**. Bivariate Analysis of Age-Related Macular Degeneration Progression Using Genetic Risk Scores. <em><ins>Genetics. 2017;206(1):119-33.</ins></em>

+ Yan Q, Ding Y, Liu Y, Sun T, Fritsche LG, Clemons T, Ratnapriya R, Klein ML, Cook RJ, Liu Y, Fan R, Wei L, Abecasis GR, Swaroop A, Chew EY, Group AR, Weeks DE, **Chen W**<sup>#</sup>. Genome-wide analysis of disease progression in age-related macular degeneration. <em><ins>Human Molecular Genetics. 2018;27(5):929-40.</ins></em>

+ Yan Q, Weeks DE, Xin H, Swaroop A, Chew EY, Huang H, Ding Y, **Chen W**. Deep-learning-based Prediction of Late Age-Related Macular Degeneration Progression. <em><ins>Nature Machine Intelligence. 2020;2(2):141-50.</ins></em>


## **D. Genomic Studies of Respiratory Diseases**

Puerto Ricans share a disproportionate burden of childhood asthma in the United States, no disease-susceptibility genes have been confidently identified in this ethnic group. Over the last decade, our collaborator Dr. Celedon and Dr. Forno has used funding from NIH and other sources and to collect genetic, epigenetic and phenotypic data in over 1000 Puerto Rican and Pittsburgh school-aged children (with and without asthma), including genome-wide (GW) genotypes, expression profiling and DNA methylation from both white blood cells and nasal epithelium. Motivated by the massive high-throughput omics datasets from our collaborator, we are interested in analyze multi-omics data in a unified framework. Understanding interactions among multi-omics data in airway epithelium should reveal epigenomic and transcriptomic profiles associated with asthma and lung function in Puerto Rican children and possibly in other ethnic groups. Particularly, we are trying to understand the following relations among DNA, RNA, methylation, and ATAC-seq data on the same cohort of samples from multiple tissues: A) Expression quantitative trait loci (eQTLs); B) Methylation quantitative trait loci (mQTLs); C) Expression quantitative trait methylations (eQTMs); D) chromatin accessibility QTLs (caQTLs). 

Major publications: 

+ **Chen W**, Boutaoui N, Brehm JM, Han YY, Schmitz C, Cressley A, Acosta-Perez E, Alvarez M, Colon-Semidey A, Baccarelli AA, Weeks DE, Kolls JK, Canino G, Celedon JC. ADCYAP1R1 and asthma in Puerto Rican children. <em><ins>American Journal of Respiratory and Critical Care Medicine. 2013;187(6):584-8.</ins></em>

+ **Chen W**, Wang T, Pino-Yanes M, Forno E, Liang L, Yan Q, Hu D, Weeks DE, Baccarelli A, Acosta-Perez E, Eng C, Han YY, Boutaoui N, Laprise C, Davies GA, Hopkin JM, Moffatt MF, Cookson W, Canino G, Burchard EG, Celedon JC. An epigenome-wide association study of total serum IgE in Hispanic children. <em><ins>The Journal of Allergy and Clinical Immunology. 2017;140(2):571-7.</ins></em>

+ Forno E, Wang T, Qi C, Yan Q, Xu CJ, Boutaoui N, Han YY, Weeks DE, Jiang Y, Rosser F, Vonk JM, Brouwer S, Acosta-Perez E, Colon-Semidey A, Alvarez M, Canino G, Koppelman GH, **Chen W**<sup>#</sup>, Celedon JC<sup>#</sup>. DNA methylation in nasal epithelium, atopy, and atopic asthma in children: a genome-wide study. <em><ins>The Lancet Respiratory medicine. 2019;7(4):336-46.</ins></em>

+ Kim S, Forno E, Yan Q, Jiang Y, Zhang R, Boutaoui N, Acosta-Perez E, Canino G, **Chen W**<sup>#</sup>, Celedon JC<sup>#</sup>. SNPs identified by GWAS affect asthma risk through DNA methylation and expression of cis-genes in airway epithelium. <em><ins>European Respiratory Journal. 2020;55(4).</ins></em>

