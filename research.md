---
title: Michael 'Misha' Rashkovetskyi's research
layout: default
---

For a brief list of publications, see [my ORCID](https://orcid.org/0000-0001-7144-2349), [ADS](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0001-7144-2349&sort=date+desc) or [my Google Scholar profile](https://scholar.google.com/citations?user=z-_StAYAAAAJ).

## Research projects

### Selection/weighting of spectroscopic (DESI) galaxies based on thermal Sunyaev-Zeldovich map

(Prof. Daniel Eistenstein)

**Goals**:

* more precise inference of standard cosmological parameters: growth of structure, matter fraction, and neutrino masses
* testing modified gravity
* studying environmental effects on galaxy-halo connection
* systematic check for the tighter constraints from density-split and density-marked (density-weighted) clustering techniques

**Tools**: Davis-Peebles estimator for the correlation function; efficient algorithm for finding close pairs in cylinders elongated along the line of sight

### Semi-analytical covariance matrices for DESI 2-point correlation function

(Prof. Daniel Eistenstein, Prof. Hee-Jong Seo, Prof. Ashley Ross, Prof. Nikhil Padmanabhan)

**Goal**: produce independent covariance matrices for 2-point function for different [Dark Energy Spectroscopic Instrument (DESI)](https://desi.lbl.gov) datasets using RascalC code from [Philcox et al 2020](https://arxiv.org/abs/1904.11070), [Philcox et al 2019](https://arxiv.org/abs/1910.04764)

**Tools**: importance sampling (Monte-Carlo) integration of analytical integrals, using interpolated 2-point correlation function; fitting to jackknife/mock covariance

**Open source**: [further development version of RascalC (library)](https://github.com/misharash/RascalC), [scripts including the DESI covariance pipeline](https://github.com/cosmodesi/RascalC-scripts)

**First-author publications**:

* **Michael Rashkovetskyi**, Daniel Forero-Sanchez, Arnaud de Mattia, Daniel J. Eisenstein, Nikhil Padmanabhan, Hee-Jong Seo, Ashley J. Ross, et al., 2024. [Semi-analytical covariance matrices for two-point correlation function for DESI 2024 data. arXiv e-prints](https://ui.adsabs.harvard.edu/abs/2024arXiv240403007R).
* **Michael Rashkovetskyi**, Daniel Eisenstein, et al., 2023. [Validation of semi-analytical, semi-empirical covariance matrices for two-point correlation function for early DESI data. Monthly Notices of the Royal Astronomical Society 524](https://ui.adsabs.harvard.edu/abs/2023MNRAS.524.3894R).

**Selected contributions**:

* Jeongin Moon, David Valcin, **Michael Rashkovetskyi**, Christoph Saulder, et al., 2023. [First Detection of the BAO Signal from Early DESI Data. arXiv e-prints](https://ui.adsabs.harvard.edu/abs/2023arXiv230408427M).
* DESI Collaboration, et al., 2024. [DESI 2024 III: Baryon Acoustic Oscillations from Galaxies and Quasars. arXiv e-prints](https://ui.adsabs.harvard.edu/abs/2024arXiv240403000D).
* DESI Collaboration, et al., 2024. [DESI 2024 VI: Cosmological Constraints from the Measurements of Baryon Acoustic Oscillations. arXiv e-prints](https://ui.adsabs.harvard.edu/abs/2024arXiv240403002D).
* DESI Collaboration, et al., 2024. [The Early Data Release of the Dark Energy Spectroscopic Instrument. The Astronomical Journal 168](https://ui.adsabs.harvard.edu/abs/2024AJ....168...58D).
* DESI Collaboration, et al., 2024. [Validation of the Scientific Program for the Dark Energy Spectroscopic Instrument. The Astronomical Journal 167](https://ui.adsabs.harvard.edu/abs/2024AJ....167...62D).

### Double-squeezed 4-point correlation function and squeezed 3-point correlation function

(Prof. Daniel Eistenstein)

**Goals (potential)**:

* develop new prescriptions for non-gaussian higher-point functions for [RascalC](https://github.com/misharash/RascalC)
* get halo occupation distribution constraints (following [Yuan et al 2018](https://arxiv.org/abs/1802.10115))
* extend halo models to "proto-halos" at 10-30 Mpc scales (following [Yuan et al 2017](https://arxiv.org/abs/1705.03464))
* probe primordial non-Gaussianity

**Tools**: efficient algorithm for alternatively binned quad/triple counting; numerical integration of disconnected 4-point function

**Open source**: [4/3/2-point function estimation code in $\mathcal O (N_{\rm galaxies}^2)$ time](https://github.com/misharash/s4PCF).

### Inhomogeneous recombination relieving Hubble tension

(Prof. Daniel Eistenstein, Dr. Julian Munoz, Prof. Cora Dvorkin)

**Goal**: investigate the idea of [relieving the Hubble tension with primordial magnetic fields](https://arxiv.org/abs/2004.09487), generalize and make forecasts

**Tools**: MCMC/nested sampling with [Cobaya](https://cobaya.readthedocs.io/en/latest/) using [CLASS](https://github.com/lesgourg/class_public) Boltzmann code

**Open source**: [modified CLASS with clumping models](https://github.com/misharash/class_public), [mock CMB likelihood for Cobaya](https://github.com/misharash/cobaya_mock_cmb).

**Publication**: **Michael Rashkovetskyi**, Julian B. Muñoz, Daniel J. Eisenstein, and Cora Dvorkin, 2021. [Small-scale clumping at recombination and the Hubble tension. Physical Review D 104](https://ui.adsabs.harvard.edu/abs/2021PhRvD.104j3517R).

### The dynamics of highly magnetized jets propagating in the medium

(Dr. Omer Bromberg, Prof. Alexander Tchekhovskoy)

**Goal**: study their launching, propagation, instabilities, energy dissipation

**Tools**: GRMHD simulations in H-AMR code (improved version of [HARM](http://rainman.astro.illinois.edu/codelib/) and [harmpi](https://github.com/atchekho/harmpi))

**My contribution**: implementing the rotating perfect conductor BC, matter injection, grid modifications, tilting the jet to avoid pole singularity issues

**Open source**: [harmpi with the neutron star boundary condition](https://github.com/misharash/harmpi).

### Pulsar losses mechanisms

(Prof. Vasily Beskin, Dr. Alexander Philippov)

**Goal**: understanding the reason of discrepancy between numerical simulations and theoretical considerations - the first give that total energy loss rate increases with inclination angle (between magnetic dipole and rotation axis), while the second gave the opposite trend

**Key results**: additional separatrix currents are important factor of radiopulsar losses reproduced in simulations; most of the energy starts flowing along open magnetic field lines already within the light cylinder; losses in numerical simulations are not dipolar

**My contribution**: analysis of electromagnetic field configuration in a force-free simulation snapshot; a method to separate polar cap from closed field lines region

**Publication**: V. S. Beskin, A. K. Galishnikova, E. M. Novoselov, A. A. Philippov, and **M. M. Rashkovetskyi**, 2017. [So how do radio pulsars slow-down?. Journal of Physics Conference Series 932](https://ui.adsabs.harvard.edu/abs/2017JPhCS.932a2012B).

### Orthogonal radiopulsars and their statistics

(Prof. Vasily Beskin, Egor Novoselov, Alisa Galishnikova, Dr. Anton Biryukov)

**Goal**: test two key models of radiopulsar period and inclination angle evolution (one theoretical by Beskin, Gurevich and Istomin (BGI) with one based on MHD and force-free simulations by Spitkovsky, Tchekhovskoy, Philippov and others) by predicting seen orthogonal pulsar numbers and comparing them to observed ones

**My contribution**: sampling pulsar distribution functions with Monte-Carlo simulation, making predictions based on it

**Publication**: E. M. Novoselov, V. S. Beskin, A. K. Galishnikova, **M. M. Rashkovetskyi**, and A. V. Biryukov, 2020. [Orthogonal pulsars as a key test for pulsar evolution. Monthly Notices of the Royal Astronomical Society 494](https://ui.adsabs.harvard.edu/abs/2020MNRAS.494.3899N).

**Open source**: [pulsar distribution sampling code](https://github.com/misharash/psr-distribution-test).

### Pulsar radiation propagation

(Prof. Vasily Beskin, Dr. Alexander Philippov)

**Goal**: understand the morphology of pulsar light-curves; find observational evidence of separatrix currents

**Method**: ray-tracing and integrating the polarization parameters according to Kravtsov-Orlov equation

**Publication**: H. L. Hakobyan, A. A. Philippov, V. S. Beskin, A. K. Galishnikova, E. M. Novoselov, and **M. M. Rashkovetskyi**, 2017. [On the light-curve anomalies of radio pulsars. Journal of Physics Conference Series 932](https://ui.adsabs.harvard.edu/abs/2017JPhCS.932a2018H).

