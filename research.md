---
layout: default
---

## Research projects

### The dynamics of highly magnetized jets propagating in the medium

(Dr. Omer Bromberg, Prof. Alexander Tchekhovkoy)

**Goal**: study their launching, propagation, instabilities, energy dissipation

**Tools**: GRMHD simulations in H-AMR code (improved version of HARM)

**My contribution**: implementing the rotating perfect conductor BC, matter injection, grid modifications, tilting the jet to avoid pole singularity issues

**Open source**: [harmpi with the neutron star boundary condition](https://github.com/misharash/harmpi).

### Pulsar losses mechanisms

(Prof. Vasily Beskin, Dr. Alexander Philippov)

**Goal**: understanding the reason of discrepancy between numerical simulations and theoretical considerations - the first give that total energy loss rate increases with inclination angle (between magnetic dipole and rotation axis), while the second gave the opposite trend

**Key results**: additional separatrix currents are important factor of radiopulsar losses reproduced in simulations; most of the energy starts flowing along open magnetic field lines already within the light cylinder; losses in numerical simulations are not dipolar

**My contribution**: analysis of electromagnetic field configuration in a force-free simulation snapshot; a method to separate polar cap from closed field lines region

**Publication**: Beskin, V. S., A. K. Galishnikova, E. M. Novoselov, A. A. Philippov, and **M. M. Rashkovetskyi**, 2017. [So how do radio pulsars slow-down?. Journal of Physics Conference Series 932, 012012](https://ui.adsabs.harvard.edu/abs/2017JPhCS.932a2012B).

### Orthogonal radiopulsars and their statistics

(Prof. Vasily Beskin, Egor Novoselov, Alisa Galishnikova, Dr. Anton Biryukov)

**Goal**: test two key models of radiopulsar period and inclination angle evolution (one theoretical by Beskin, Gurevich and Istomin (BGI) with one based on MHD and force-free simulations by Spitkovsky, Tchekhovskoy, Philippov and others) by predicting seen orthogonal pulsar numbers and comparing them to observed ones

**My contribution**: sampling pulsar distribution functions with Monte-Carlo simulation, making predictions based on it

**Publication**: Novoselov, E. M., V. S. Beskin, A. K. Galishnikova, **M. M. Rashkovetskyi**, and A. V. Biryukov, 2020. [Orthogonal pulsars as a key test for pulsar evolution. Monthly Notices of the Royal Astronomical Society 494, 3899-3911](https://ui.adsabs.harvard.edu/abs/2020MNRAS.494.3899N).

**Open source**: [pulsar distribution sampling code](https://github.com/misharash/psr-distribution-test).

### Pulsar radiation propagation

(Prof. Vasily Beskin, Dr. Alexander Philippov)

**Goal**: understand the morphology of pulsar light-curves; find observational evidence of separatrix currents

**Method**: ray-tracing and integrating the polarization parameters according to Kravtsov-Orlov equation

**Publications**:

* Hakobyan, H. L., A. A. Philippov, V. S. Beskin, A. K. Galishnikova, E. M. Novoselov, and **M. M. Rashkovetskyi**, 2017. [On the light-curve anomalies of radio pulsars. Journal of Physics Conference Series 932, 012018](https://ui.adsabs.harvard.edu/abs/2017JPhCS.932a2018H).
* Hakobyan, H. L., A. A. Philippov, V. S. Beskin, A. K. Galishnikova, E. M. Novoselov, and **M. M. Rashkovetskyi**, 2018. [On the Light-Curve Anomalies of Radio Pulsars. Workshop on Astrophysical Opacities 515, 295](https://ui.adsabs.harvard.edu/abs/2018ASPC..515..295H).

