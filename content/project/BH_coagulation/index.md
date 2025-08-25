---
title: Black hole coagulation
date: 2020-08-18
links:
  - type: site
    url: https://github.com/jordanflitter/BH-coagulation
---

Code for solving the coagulation equation for black hole and neutron star mergers in dense clusters and predicting the observed black hole mass function by gravitational-wave detectors.

The main equation that the code solves is the discrete [coagulation (Smoluchowski) equation](https://en.wikipedia.org/wiki/Smoluchowski_coagulation_equation), 

$$\dot N_i=\frac{1}{2}\sum_{j=1}^{i-1}R_{i-j,j}N_{i-j}N_j-\sum_{j=1}^{\infty}R_{i,j}N_iN_j.$$

Here, $N_i$ is the number of black holes of mass $M_i$ while $R_{i,j}N_iN_j$ is the merger rate of black holes of mass $M_i$ and $M_j$. This first term on the RHS thus increases $N_i$ due to mergers of smaller black holes (that result in a remnant mass of $M_i$), while the second term lowers $N_i$ due to mergers between $M_i$ and any other black hole. This equation however needs to be modified in order to simulate a realistic cluster dynamics, since it implictly assumes that all black holes remain in the cluster, that there is no mass loss due to gravitational-wave emission, and that the mergers happen instantaneously once a black hole binary was formed. See more information at [arxiv: 2008.10389](https://arxiv.org/pdf/2008.10389).

Let us assume for example that we have a cluster that initially contains 300 black holes of different masses. The following plots show the total number and total mass of the black holes in the cluster, with different ejection models. In all models, the total number of black holes decreases over time (due to mergers) as well as the total mass (unless there are no ejections).

{{< figure src="N and M vs time.png" caption="" width="100%" >}}

We can also study how different interaction rates affect the final black hole mass function and the probability for intermediate-mass black hole (IMBH) formation, this is a black hole of mass greater than 500 solar masses. In the plots below, the interaction rate is modeled as $R_{i,j}\propto\left(\frac{\min\left(M_i,M_j\right)}{\max\left(M_i,M_j\right)}\right)^\beta\left(M_i+M_j\right)^{\gamma}$, and $\beta$ and $\gamma$ are zero, unless the legend says otherwise. Interestingly, while positive $\gamma$ and negative $\beta$ models allow IMBH fromation, the final black hole mass function looks very different!

{{< figure src="IMBH and BHMF.png" caption="" width="100%" >}}




<!--more-->
