---
title: "Research about the nontraditional Coriolis terms"
excerpt: "My main project (2018-) with 5 publications<br/><img src='/images/ITCZ.png'>"
collection: portfolio
---

<iframe width="560" height="315" src="https://www.youtube.com/embed/1tqL_pgOkcs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Zonal temporal dispersion relations of the equatorially confined wave solutions with (black) and without (red) the nontraditional Coriolis terms (NCTs). Except the last frame of the animation, sound of piano is played at a sound frequency proportional to the effective buoyancy frequency used to plot every frame. (From [Ong and Roundy 2020](https://hingong.github.io/publication/2020-10-15-paper-title-number-4)) 

NCTs represent components of [Coriolis force](https://en.wikipedia.org/wiki/Coriolis_force#E%C3%B6tv%C3%B6s_effect) that turn eastward motion upward and upward motion westward, and vice versa.

NCTs, long neglected in global atmospheric models, significantly influence tropical circulation. Over the past seven years, I have uncovered several dynamic pathways through which NCTs alter the tropical circulation. I am leading a cross-institutional project to incorporate NCTs into [CESM3](https://www.cesm.ucar.edu/) and [E3SM](https://docs.e3sm.org/) using two nonhydrostatic dynamical cores, Spectral Element and MPAS [(Skamarock, Ong, and Klemp, 2021)](https://doi.org/10.1175/MWR-D-20-0286.1). Our results suggest that omitting NCTs can be a contributor to the long-standing double intertropical convergence zone (ITCZ) bias in models.

<img src='/images/NCT_hierarchy.png'>

The above figure outlines a model hierarchy for NCT effects. In the nonturbulent regime, NCTs modify the pressure–height relation by making westward-moving mass appear heavier and vice versa [(Ong & Roundy, 2020a)](https://doi.org/10.1002/qj.3703). This effect is involved in two categories of NCT impacts:

•	The compressional beta effect drives compressional Rossby waves eastward ([Gilman & Glatzmeier, 1981](https://doi.org/10.1086/190714); [Verhoeven & Stellmach, 2014](https://doi.org/10.1016/j.icarus.2014.04.019); [Ong & Roundy, 2020b](https://doi.org/10.1175/JAS-D-20-0124.1); [Ong & Yang, 2022](https://doi.org/10.1175/JAS-D-21-0219.1)). When co-existing with the planetary beta effect, there are mixed planetary–compressional Rossby waves ([Bekki et al., 2022](https://doi.org/10.1051/0004-6361/202243164); [Ong & Yang, 2025](https://doi.org/10.1175/JAS-D-24-0253.1)).

•	In the flow response to heating, NCTs drive easterly winds in diabatic heating zones ([Hayashi & Itoh, 2012](https://doi.org/10.1175/JAS-D-11-0334.1); [Ong & Roundy, 2019](https://doi.org/10.1002/qj.3572); [Igel & Biello, 2020](https://doi.org/10.1175/JAS-D-20-0024.1); [Marsico et al., 2023](https://doi.org/10.1175/JAS-D-22-0254.1)), which further concentrate ITCZ precipitation toward the equator via Ekman transport (Ong et al., 2025, abstract).

In the turbulent regime, NCTs affect the upscale turbulent momentum transport ([LeMone, 1983](https://doi.org/10.1175/1520-0469(1983)040<1815:MTBALO>2.0.CO;2); [Verhoeven & Stellmach, 2014](https://doi.org/10.1016/j.icarus.2014.04.019); [Goldsmith et al. 2025](https://doi.org/10.1175/JAS-D-24-0160.1)). I derived the full Reynolds stress equations with NCTs and introduced them into the CLUBB parameterization used in CESM3 (Ong & Larson, ongoing).
