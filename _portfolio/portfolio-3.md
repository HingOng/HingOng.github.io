---
title: "Research about Atmospheric Convection"
excerpt: "My previous main project (2015-2017) with 1 publication<br/><img src='/images/Research3.png' width='400'>"
collection: portfolio
---

<img src='/images/Research3.png' width='400'>

The schematic vertical cross sections for HYMACS are depicted as follows: (a) the scale of a convective updraft and a mass-compensating environment compared with the size of grid columns; (b) how subgrid-scale mass convergence or divergence is treated in a grid column; and (c) how grid-scale dynamics respond to the subgrid-scale mass source and sink. (From [Ong et al. 2017](https://hingong.github.io/publication/2017-06-23-paper-title-number-1))

Motivation
====

Representing subgrid-scale convective processes in atmospheric models presents unique challenges. Existing models often rely on local compensation of convective mass flux within a grid cell, a practice sensitive to grid resolution.

Modeling approaches
====
To address this issue, I adapted the Kain-Fritsch convective parameterization scheme, allowing it to parameterize convective drafts while leaving the compensating motion for the model dynamics to resolve. I developed a model hierarchy to test the effects of the imposed local compensation (Ong, Wu, & Kuo 2017).

Main finding
====

My research demonstrated that this novel approach leads to less sensitivity to changes in grid-cell width, particularly in dynamic responses to subgrid-scale convective updraft. Additionally, I found that the imposed local compensation at certain resolutions could significantly affect simulated tropical cyclone dynamics (Ong, Wu, & Kuo 2017).

Model evolved
====

My work has directly contributed to the advancement of the Weather Research and Forecasting (WRF) model, incorporating this novel approach (Ong, Wu, & Kuo 2017).

Modeling peers inspired
====

My research has inspired modeling peers, notably the European Centre for Medium-range Weather Forecast (ECMWF) Integrated Forecast System (IFS), to explore similar methods for representing convection ([Malardel & Bechtold 2019](https://doi.org/10.1002/qj.3528)).

Broader Impact and Prospects
====

This project underscores the need for improved representation of convection in weather and climate models, particularly as computational resources allow for finer model grids. The ongoing exploration of this area holds promise for refining model accuracy and reliability.

Project Status
====

I have switched to other projects while other people keep going, e.g., see [Cited by](https://scholar.google.com/scholar?oi=bibs&hl=en&cites=6871585193749678458&as_sdt=5)

Publication
====

[Ong, H., Wu, C. M., & Kuo, H. C. (2017). Effects of artificial local compensation of convective mass flux in the cumulus parameterization. <i>J. Adv. Model. Earth Syst., 9</i>(4), 1811-1827.](https://hingong.github.io/publication/2017-06-23-paper-title-number-1)
