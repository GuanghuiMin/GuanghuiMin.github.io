---
layout: project
title: Analysis of Beijing PM 2.5 Dataset Using MCMC-glmm
subtitle: Use MCMC simulation for parameter estimation
---

[[slide]](https://drive.google.com/file/d/1Te4dA4cANXVrGKs8nFDkdE-64cmrt6aj/view?usp=drive_link)

The presented project focuses on the modeling of PM 2.5 data in Beijing, considering the influence of weather conditions. To accomplish this task, a generalized linear mixed model (GLMM) is employed, which allows for the incorporation of both fixed and random effects in the analysis.

The project utilizes a Bayesian hierarchical modeling approach, coupled with the **Monte Carlo Markov Chain (MCMC) method**, to estimate the model parameters. This Bayesian framework provides a robust and flexible approach to handle the complexities of the data and capture the uncertainties associated with the parameter estimates.

An essential aspect of the project involves assessing the stability of the parameter estimates. This is accomplished through the analysis of autocorrelation plots and trace plots, which provide insights into the convergence and mixing properties of the MCMC algorithm. These diagnostic plots offer valuable information for ensuring the reliability and accuracy of the estimation process.

{%
	include image_with_caption.html
	url="/assets/projects/stats_lmm/trace_plot.png"
	width="100%"
%}

By combining the PM 2.5 data with the corresponding weather conditions, the GLMM enables the investigation of the relationship between air pollution levels and various meteorological factors. This modeling approach accounts for both fixed effects, representing the systematic influences of weather conditions, and random effects, capturing the variability across different locations or time points.
{%
	include image_with_caption.html
	url="/assets/projects/stats_lmm/main.png"
	width="100%"
%}

The project's contributions lie in its ability to provide a comprehensive analysis of the PM 2.5 data in Beijing, considering the complex interplay between air pollution and weather conditions. By employing the GLMM and Bayesian hierarchical modeling techniques, the project offers a robust and statistically rigorous approach to estimate the model parameters and gain insights into the underlying relationships.

The use of MCMC methods ensures that the estimation process is reliable and produces stable results. The autocorrelation plots and trace plots serve as important diagnostic tools to assess the convergence and mixing properties of the MCMC algorithm, providing confidence in the reliability and adequacy of the parameter estimates.

Overall, the Generalized Linear Mixed Model for PM 2.5 Data Analysis project represents a significant advancement in understanding the factors influencing air pollution in Beijing. By incorporating weather conditions into the modeling framework, the project provides valuable insights into the relationship between PM 2.5 concentrations and meteorological factors. The application of Bayesian hierarchical modeling and MCMC methods ensures robust parameter estimation and enhances our understanding of the complex dynamics of air pollution in urban environments.