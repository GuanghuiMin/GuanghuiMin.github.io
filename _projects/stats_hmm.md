---
layout: project
title: Asset Allocation using Regime-switching Hidden Markov Method
subtitle: Cluster time series data and construct portfolio
---
A hidden Markov model (HMM) is a statistical Markov model in which the system being modeled is assumed to be a Markov process — call it with unobservable ("hidden") states. 

The Asset Allocation using Regime-switching Hidden Markov Method is an innovative project that aims to quantitatively characterize the **performance rotation** of assets based on a regime-switching Hidden Markov Model. This approach goes beyond the traditional Merrill Lynch Clock model and offers a comprehensive analysis of market dynamics and asset classes.

The project incorporates five major asset classes: large-cap stocks, small-cap stocks, corporate bonds, government bonds, and gold. By conducting time-series clustering of market performance across different regimes, the project identifies patterns and trends in the returns of these asset classes.
{%
	include image_with_caption.html
	url="/assets/projects/stats_hmm/main.png"
	width="100%"
%}

A crucial aspect of the project is **the selection of the number of regimes**, which is achieved through a rigorous variable selection process using k-fold cross-validation. The chosen model is then subjected to economic interpretations to provide valuable insights and understanding.

The project encompasses various stages, all of which were completed independently. This includes meticulous data preparation, comprehensive data analysis, modeling using the regime-switching Hidden Markov Model, cross-validation techniques, and the presentation of results.

One notable outcome of the project is the construction of an asset allocation portfolio based on the developed model. The portfolio allocation combines the insights from the regime-switching Hidden Markov Model with risk parity weight allocation techniques. This portfolio is currently undergoing live testing and has demonstrated stable performance amid significant global economic fluctuations.

{%
	include image_with_caption.html
	url="/assets/projects/stats_hmm/portfolio.png"
	width="100%"
%}

Compared to the benchmark, the asset allocation portfolio generated an impressive **excess return of 4.2% in the recent year**. This performance showcases the effectiveness and robustness of the model in capturing opportunities and managing risks in the dynamic investment landscape.

The Asset Allocation using Regime-switching Hidden Markov Method project represents a significant advancement in asset allocation strategies. By utilizing an innovative modeling approach, conducting thorough analysis, and incorporating risk management techniques, the project provides investors and financial professionals with a valuable tool for optimizing asset allocation decisions in the face of changing market conditions.