---
title: "Research about dynamic compensation of convective mass flux"
excerpt: "My previous main project (2015-2017) with 1 publication<br/><img src='/images/Research2.png' width='400'>"
collection: portfolio
---

<img src='/images/Research2.png' width='400'>

The schematic vertical cross sections for HYMACS are depicted as follows: (a) the scale of a convective updraft and a mass-compensating environment compared with the size of grid columns; (b) how subgrid-scale mass convergence or divergence is treated in a grid column; and (c) how grid-scale dynamics respond to the subgrid-scale mass source and sink. (From [Ong et al. 2017](https://hingong.github.io/publication/2017-06-23-paper-title-number-1))

Motivation
====

Because of the need for more-accurate atmospheric models that are used to predict weather and climate, I studied a particular assumption in the atmospheric models and found it erroneous. Specifically, I investigated the assumption to impose mass compensation within a model cell. Atmospheric convection is essential to climate, but most climate models cannot resolve convection and must parameterize the bulk effects of unresolved convection. In atmospheric convection, convective drafts bring air mass up or down, and a wider environment brings air mass back in compensation. Conventional convective parameterization imposes local compensation of convective mass flux within a grid cell. However, with increasing computer resources, models can run with grid cells narrower than the environment but still wider than convective drafts; that is, the gray-zone resolution.

Summary
====

My research used a widely used convective parameterization scheme called Kain-Fritsch (KF) scheme a state-of-the-art model called the Weather Research and Forecasting (WRF) Model. I adapted KF scheme into a hybrid mass flux cumulus scheme so that it parameterizes convective drafts but leaves the compensating motion for model dynamics to resolve. With this scheme, I tested the dynamic response of air flow to a prescribed mass lifting and found that the dynamic response to subgrid-scale convection becomes less sensitive to changes in grid-cell width than the conventional approach. Also, I simulated tropical cyclone development and found the imposed local compensation at the gray-zone resolution could cause significant effects on tropical cyclone dynamics. Hence, when improving the resolution of our atmospheric models to the gray-zone, we should avoid the artificial local compensation for convective parameterization, and HYMACS is a simple and useful remedy to dynamically distribute the mass compensation.
Broader Impact
====

This project is important because it points out a problem and a remedy in representing convection in weather and climate models when computer resources allow finer model grids than in tradition, which may lead to model development that improves prediction, which improves our lives.

Project Status
====

I have switched to other projects while other people keep going, e.g., see [Cited by](https://scholar.google.com/scholar?oi=bibs&hl=en&cites=6871585193749678458&as_sdt=5)

Publication
====

[Ong, H., Wu, C. M., & Kuo, H. C. (2017). Effects of artificial local compensation of convective mass flux in the cumulus parameterization. <i>J. Adv. Model. Earth Syst., 9</i>(4), 1811-1827.](https://hingong.github.io/publication/2017-06-23-paper-title-number-1)
