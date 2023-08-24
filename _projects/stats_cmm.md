---
layout: project
title: Coupled Mixed Model for Joint Genetic Analysis
subtitle: Application to Alzheimer’s Disease and Substance Use Disorder
---
**Acknowledged by Dr. [Haohan Wang](https://haohanwang.github.io/)**

[[Paper]](https://www.biorxiv.org/content/10.1101/336727v2)   

[[code]](https://github.com/GuanghuiMin/CMM)

[📚[My Contribution]](https://drive.google.com/file/d/1FNVPzOf6gd-6WKJSvoJU7Y-UJTLPcv76/view?usp=drive_link)

Over the past decade, Genome-wide Association Studies (GWASs) have played a pivotal role in deciphering the human genome and identifying genetic variations associated with diseases. However, a promising approach called "joint analysis," which involves analyzing multiple independently generated GWAS datasets, has remained largely in its preliminary stages. This project aims to address this gap by proposing an innovative method known as the Coupled Mixed Model (CMM).

The CMM method enables the joint analysis of GWAS on two independently collected datasets, even when they exhibit different phenotypes. It achieves this by leveraging a set of multivariate sparse mixed models and employing statistical learning modeling to infer uncollected phenotypes. Notably, the CMM method takes into account confounders arising from population stratification, family structures, cryptic relatedness, and other confounders commonly encountered in joint genetic studies.

The project introduces several key contributions. Firstly, a Bayesian maximum likelihood model is proposed to handle multi-correlated responses data, particularly when the design matrix contains missing values. The objective is to make predictions utilizing same-distribution sampled data to the greatest extent possible. To optimize the loss function, the Alternating Direction Method of Multipliers (ADMM) algorithm is applied, and its convergence is proven using a block coordinate method.

The performance of the CMM method is thoroughly evaluated and compared against competing methods, including the baseline linear mixed model. The superiority of the CMM method is demonstrated through box plots of the area under ROC curves (auROC), which accurately identify the Single Nucleotide Polymorphisms (SNPs) jointly responsible for both phenotypes as well as specifically for Phenotype 1.

{%
	include image_with_caption.html
	url="/assets/projects/stats_cmm/eval.png"
	width="100%"
%}

Additionally, the project involves the derivation of early formulas and the execution of experiments and validations on small datasets. The results obtained from these rigorous evaluations contribute to the development and refinement of the proposed Bayesian maximum likelihood model. The project's significance is further underscored by the acknowledgment and appreciation received from the authors, with the project member's name listed in the Acknowledgments section of the published paper.

To validate the effectiveness of the CMM method, simulation experiments are conducted. Furthermore, a real data joint analysis is performed on two independent datasets specifically generated to investigate the genetic associations of Alzheimer's disease and substance use disorder, respectively. The outcomes of these analyses reveal new insights into these diseases, shedding light on their genetic underpinnings and potential avenues for further research.

Overall, this project bridges the gap in joint analysis in GWAS by introducing the Coupled Mixed Model (CMM) method. By accommodating different phenotypes, addressing confounders, and leveraging advanced statistical techniques, the project significantly advances the field of genetic research. The promising results and novel insights obtained from this project hold the potential to drive future breakthroughs in deciphering the complex relationship between genetics and diseases, ultimately contributing to advancements in personalized medicine and healthcare.