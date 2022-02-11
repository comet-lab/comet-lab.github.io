---
layout: paper
title: "Identification of Tissue Optical Properties During Thermal Laser-Tissue Interactions: An Ensemble Kalman Filter-Based Approach"
year: "2022"
shortref: "Arnold & Fichera Numerical Methods in BME 2022"
#nickname: nobel-prize-arnold
journal: "International Journal for Numerical Methods in Biomedical Engineering"
#volume:
#issue:
#pages:
authors: "Arnold A, Fichera L"
image: /assets/images/papers/numerical-methods-bme-2022-cover.jpg
redirect_from:
fulltext:
pdf: https://arxiv.org/abs/2107.10340
#pdflink: https://arxiv.org/abs/2107.10340
github:
pmid:
pmcid:
f1000:
doi: "10.1002/cnm.3574"
dryad_doi:
figshare_doi:
altmetric_id:
category: paper
published: true
embargo: false
peerreview: true
review: false
tags:
---
{% include JB/setup %}

# Abstract
In this article, we propose a computational framework to estimate the physical properties that govern the thermal response of laser-irradiated tissue. We focus in particular on two quantities, the absorption and scattering coefficients, which describe the optical absorption of light in the tissue and whose knowledge is vital to correctly plan medical laser treatments. To perform the estimation, we utilize an implementation of the ensemble Kalman filter (EnKF), a type of Bayesian filtering algorithm for data assimilation. Unlike prior approaches, in this work, we estimate the tissue optical properties based on observations of the tissue thermal response to laser irradiation. This method has the potential for straightforward implementation in a clinical setup, as it would only require a simple thermal sensor, for example, a miniaturized infrared camera. Because the optical properties of tissue can undergo shifts during laser exposure, we employ a variant of EnKF capable of tracking time-varying parameters. Through simulated experimental studies, we demonstrate the ability of the proposed technique to identify the tissue optical properties and track their dynamic changes during laser exposure, while simultaneously tracking changes in the tissue temperature at locations beneath the surface. We further demonstrate the framework's capability in estimating additional unknown tissue properties (i.e., the volumetric heat capacity and thermal conductivity) along with the optical properties of interest.
