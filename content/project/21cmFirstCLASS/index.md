---
title: 21cmFirstCLASS
date: 2023-09-07
links:
  - type: site
    url: https://github.com/jordanflitter/21cmFirstCLASS
---

21cmFirstCLASS is an extension of the popular [21cmFAST](https://github.com/21cmfast/21cmFAST) code that interfaces with [CLASS](https://github.com/lesgourg/class_public) to generate initial conditions at recombination that are consistent with the input cosmological model. These initial conditions can be set during the time of recombination, allowing one to compute the 21cm signal (and its spatial fluctuations) throughout the dark ages, as well as in the proceeding cosmic dawn and reionization epochs, just like in the standard 21cmFAST.

Below we can see the theoretical shape of the 21cm signal and its evolution over time (or redshift, $z$). The top panel presents the "global signal" (as averaged over the entire sky) while the bottom panel also shows the spatial fluctuations in the signal. 

{{< figure src="lightcone_boxes.png" caption="" width="100%" >}}

We can examine the spatial fluctuations in the signal better if we plot the "coeval boxes" of the simulation at different redshifts. At high redshifts (early times), the fluctautions are small and can be described by linear perturbation theory. At low redshifts (late times) the fluctuations become highly non-linear.

{{< figure src="coeval_boxes.png" caption="" width="100%" >}}

21cmFirstCLASS has been used in many works to study how much information the 21cm signal could give us on different models of dark matter [[1](https://arxiv.org/pdf/2207.05083), [2](https://arxiv.org/pdf/2309.03942), [3](https://arxiv.org/pdf/2410.01486), [4](https://arxiv.org/pdf/2407.19549)], dark energy [[5](https://arxiv.org/pdf/2410.22424)], neutrinos [[6](https://arxiv.org/pdf/2504.15348)], as well as star formation [[7](https://arxiv.org/pdf/2310.03021)] and primordial magnetic fields [[8](https://arxiv.org/pdf/2308.04483)]. In addition, 21cmFirsCLASS has been used to improve our understanding during the dark ages [[9](https://arxiv.org/pdf/2309.03948), [10](https://arxiv.org/pdf/2411.00089)].

<!--more-->
