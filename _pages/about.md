---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# About me
# ======
My major interest is in the use of Bayesian data analysis to generate personalised descriptions of metabolic health from wearable device data.

I completed my PhD in Systems Biology at the University of Manchester (UK) (thesis title: "Modelling and analysis of oscillations in gene expression through neural development"), where I was supervised by Nancy Papalopulu and co-supervised by Magnus Rattray. In 2016 I then moved to the EPFL (Switzerland) to start a postdoc with Felix Naef, where I continued to work on projects related to stochastic gene expression in the context of stem cells and circadian rhythms.

In 2019 I received a Transition Postdoc Fellowship (TPdF) from Personalized Health and Related Technologies (PHRT), Switzerland. We started a collaboration with Tinh-Hai Collet (HUG, Geneva) on a new study called "The Multi-Sensor Study". I've been working as a researcher in Tinh-Hai's group at the HUG in Geneva since November 2021. We're currently applying the methodology developed during the Multi-Sensor Study to other projects related to gestational diabetes and time-restricted eating.

Research Projects
======

Combining wearable technologies, smartphone apps, and Bayesian data integration to understand human metabolic health
------

At the beginning of my PHRT transition postdoc fellowship, we collaborated with Tinh-Hai Collet on the SwissChronoFood project. Using food and drink recorded with a smartphone application, we showed that the processing level of food (using the NOVA classification system) has the highest number of significant relationships with metabolic syndrome components after age and sex. 

We are currently finalising a study entitled “the Multi-Sensor Study”. The fun part of this project for me has been the involvement at all steps of the study, from study design, writing of the ethics proposal, participant recruitment, experiment organisation, data collection, statistical model development, and (let's hope soon!) publication.

Now that I'm based in Tinh-Hai's group in Geneva, we are collaborating with Prof. Jardena Puder (CHUV) and Prof. Charna Dibner (UNIGE) on a large project funded by the Leenaards Foundation, the Vontobel Foundation and the SwissLife Jubiläumsstiftung for data collection and lab analyses. While the Multi-Sensor Study was an observational study in a healthy population, we are now translating this data analysis methodology into a global health problem (gestational diabetes) and an interventional study (with time-restricted eating). 

The circadian clock at the single-transcript level
------

While rhythmic gene expression of circadian genes is well-described in populations of cells, the single-cell mRNA dynamics of core-clock genes remains largely unknown. My colleague at the EPFL Alice Hugues used single molecule fluorescence in-situ hybridization (smFISH) at multiple time points to measure pairs of core-clock transcripts in mouse fibroblasts at single-molecule resolution. We developed a probabilistic model for multivariate mRNA counts using mixtures of negative binomials, which accounts for transcriptional bursting, circadian time and cell-to-cell heterogeneity, notably in cell size. Decomposing the mRNA variability into distinct noise sources showed that clock time contributes a small fraction of the total variability in mRNA number between cells.

Transcriptional memory in stem cells
------

Upon moving to the Naef lab at the EPFL, I started a collaboration with the lab of David Suter (EPFL), where the goal was to quantify the relationship in gene expression between sister cells in embryonic stem cells after cell division. Using techniques based on Gaussian processes, we were able to quantify the propagation of transcriptional activity over time and across cell generations (Phillips, Nat Comms, 2019).

Identifying oscillations in single-cell live-imaging data
------

Multiple biological processes are driven by oscillatory gene expression at different time scales, but stochastic gene expression blurs the boundaries between aperiodic fluctuations and noisy oscillators. This creates a challenge for determining whether a single-cell gene expression profile is oscillating or not, because neither intuition nor pre-existing methods work well for identifying oscillatory activity in noisy biological time series. We created a statistical method for classifying whether an experimentally derived noisy time series is periodic using non-parametric regression with Gaussian processes. Our method can distinguish oscillatory gene expression from random fluctuations of non-oscillatory expression in single-cell time series, despite peak-to-peak variability in period and amplitude of single-cell oscillations.

Mathematical models of emergent dynamics in stem cell decision-making
------

At the beginning of my PhD, my research focus on the bottom-up mathematical description of gene regulatory networks in neural stem cells. Specifically, we wanted to understand how the regulation of an oscillatory transcription factor by a micro-RNA could control the timing of neural differentiations. Originally, the work was based on deterministic dynamical models (Goodfellow, Nat Comms 2014), but I then extended the model to incorporate stochastic gene expression and performed an in-depth investigation into the consequences of biological noise on the timing of differentiation (Phillips, eLife 2016).

