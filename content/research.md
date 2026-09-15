---
title: "Research"
description: "Overview of current and recent research."
hidemeta: true
---
---

My PhD and postdoc research are highly contrasting, below I summarize my work under the two main headings. Going forward, I look forward to mixing both of my research interest to investate the interplay of supramolecular (nanosystem) chirality and spin chemistry. Since spin effects (such as chiral induced spin selectivity CISS) appear to be extensive in system size, new fundamental theories of spin-nuclear correlation must be adapated to highly scalable electronic stucture theory methods that can treat systems of large molecular size.

---

## Phase space electronic structure and spin–nuclear coupling

{{< figure src="/Spin_coriolis_for_website.png" alt="Schematic of static versus dynamic spin, and a methyl radical with electronic spin and nuclear momenta." caption="(left) BO potential energy surfaces that show regions of dyanamic (weak $\to$ large energy gap) electron-nuclear correlation that PS methods treat, and strong electron-nuclear correlation, where traditional nonadiabatic methods like surface hopping and Ehrenfest dynamics are appropriate. (right) The phase space electronic surfaces in nuclear momentum (rather than a position reaction coordinate!) for a rotation of a methyl radical. Broken spin symmetry solutions for clockwise vs counterclockwise nuclear rotation are observed. " align="center" >}}

Phase space (PS) electronic strcuture theory  is a novel approach to address electron-nuclear correlation going beyond the Born-Oppenheimer(BO) approximation. Nearly all modern electronic structure theory assumes the BO approximation as its primary starting point, where the electronic Schroedinger equation is parametrized by the static ionic postitions ($\mathbf{R}$) of the nuclei. By contrast, PS theories are parametrized by both nuclear postitions and momenta ($\mathbf{P}$), by performing a Wigner transform on the full adiabatic electron-nuclear Hamiltonian. Crucially, it is now possible for exchange of momenta between nuclei and electrons and spin. As a semiclassical approximation of the full adiabatic Born-Huang framework, PS theory best captures dynamic electron-nuclear correlation, akin to dynamic electron-electron correlation methodologies like MP2 and GW field theories in standdard electronic structure theory.

My primary contribution to the devlopment of PS theory over the last two years is the proposal, phenomenological investigation, and then exact benchmarking of a proposed spin Coriolis force. The spin coriolis force will drive a spin out of the lab rest frame and into the relative "body frame" of the nuclei. With this in mind, the actually minimization of the total energy will now involve minimizing the total (nuclear+elctronic+spin) angular momentum, leading to the spin symmetry breaking pictured below. In spectroscopy, spin symmetry breaking is observed in sigma states of small radical molecules known as spin rotation splitting. In a Pi doublet state, this same phenomena is referred to as $\Lambda$-doubling. 

---



## Stochastic Bethe–Salpeter spectra for nanosystems and complex chromaphores and their aggregates.

{{< figure src="/BSE_fig_for_website.png" alt="10-CPP plus C60 structure next to Bethe–Salpeter spectra comparing stochastic sampling of the screened interaction." caption=" Structure of a polymer wrapped buckball 10-CPP+C$_{60}$ next to exact Bethe Salpeter spectra and varying stochastic approximations to the true screened Coulomb interaction $W(r,r')$." align="center" >}}

My PhD focused on expanding the suite of stochastic electronic structure methods to the Bethe-Salpeter equation (BSE) for excitons. Due to the nature of using the true dielectric function of the material $\epsilon(r)$ for forming the screened Coulomb interaction $W(r,r')$, BSE spectra are often much more accurate for unusually delocalized excitons and charge transfer excitions. I delevoped techniques for stochastically sampling $W$, for extracting the translationally invariant portion of $W(r,r') \to v_W(|r-r'|)$, which can be treated as a traditional exchange opperator with dielectric screening. 

Big successes of this new methodology include:predicting the accurately spectra of large delocalized near-infrared dye molecules with excitations as low as 1 eV, conquering the so-called `cyanine-problem' of TD-DFT, and predicting protein emvironment renormalization of the excitons in the dye-aggregate reaction complex center of photosystem-II (a system of over 3000 electrons!).