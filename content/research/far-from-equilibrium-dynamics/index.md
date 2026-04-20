---
title: "Far-from-equilibrium Quantum Many-body Dynamics"
summary: "Understanding quantum systems out of equilibrium"
date: 2026-04-19T00:00:00Z
type: page

design:
  spacing: '3rem'
---

Quantum simulators have allowed us to peak into a realm otherwise obscured in traditional materials and enabled novel insights into far-from-equilibrium and non-ergodic dynamics in many-body quantum systems. 

## Thermalisation in quantum systems
What does it mean for a closed quantum system to thermalise? By assumption, the system undergoes unitary dynamics described by the Schrödinger equation. Therefore, it is a priori not clear how to even speak about thermalisation in such a context. 

A deep insight that underpins much of our current understanding of quantum many-body dynamics is the so-called "Eigenstate Thermalisation Hypothesis". It states that, under certain assumptions, a quantum many-body state at a well-defined energy will **locally** be indistinguishable from a **thermal state** with that average thermal energy. Without any particular structure to the system, this gives a mechanism for thermalisation of closed quantum systems. In particular, through many-body dynamics local observables experience dephasing, whereby the long-time behaviour is accurately described by the distribution over the energy states of the system. This effectively describes a steady state that can directly be linked to a thermal ensemble. Only if one probes the system on macroscales, does it become clear that it remains pure. 

In many situations, there even exists a deep link between the thermal entropy of the system and its entanglement properties. In particular, the bipartite von Neumann entanglement entropy at energy E can be directly linked to the thermal entropy at that thermal average energy. 

## Non-thermal dynamics
Over the last two decades, a lot of effort has been devoted to understanding with greater detail under which conditions quantum systems thermalise (in the sense described above), by pin-pointing situations where highly non-thermal behaviour ensues. Four main mechanisms for such behaviour has, hereby, been identified

- **Integrability.** Quantum systems with many symmetries are associated with modified thermal ensembles. The main idea is that an **extensive** set of symmetries leads to highly constrained dynamics that strongly modifies the reached steady state. This has led to the development of **generalised Gibbs ensembles** as well as **generalised hydrodynamics**. 
- **Many-body localisation.** In 1958, P. W. Anderson first described his localisation phenomenon for non-interacting particles (now known as Anderson localisation). This intriguing mechanism describes how particles become localised due to **disorder**, which has been hugely important for our understanding of solid state materials, especially ones constrained to one or two dimensions. The possibility of extending this phenomenon to interacting many-body systems has in the last two decades seen an impressive surge, and remains a highly active research areas with many open questions. 
- **Hilbert space fragmentation.** This novel development describes how the states of a quantum system may separate, or fragment, into **exponentially** many disconnected sectors. In this manner, thermalisation can at most be achieved within each sector. In this manner,  states belonging to separate sectors, that otherwise resemble each other, can exhibit highly distinct dynamics. In principle, this framework is mainly an extension of the phenomenology related to integrable systems. However, unlike most known integrable systems, the symmetries involved in fragmentation often have a highly non-local character. 
- **Quantum many-body scars.** The above three mechanisms generally affect the entire spectrum of states. On the contrary, many-body scars are rare exceptions to otherwise "thermal" spectra. These were first discovered in Rydberg array quantum simulators, in which they lead to long-lived oscillations of local observables for a small subset of initial states. Different mechanisms for the appearance of these states have been identified, including dynamical symmetries and Fock space cages. 


## My Contributions

My contributions to understanding far-from-equilibrium dynamics include:

- **Discovery of symmetry-protected non-ergodic dynamics** in quantum magnets, and associated thermodynamic stability of magnetic domains far from equilibrium
- **Investigation of dopant thermalization** in quantum spin lattices
- **Discovery of self-similar scaling** in dopant transport with associated non-Gaussian diffusion. 

## Key Publications

- **P. Kos** et al. "Magnetic domains stabilized by symmetry-protected zero modes" (2026) - Demonstrates highly non-ergodic dynamics of quantum magnets stable in the thermodynamic limit and protected by chiral symmetry
- **Yang, M., Anand, S., Nielsen, K.K.** "Beyond fragmented dopant dynamics in quantum spin lattices: Robust localization and non-Gaussian diffusion" *Physical Review B* (2025) - Comprehensive analysis of non-equilibrium dopant dynamics

## Methodologies

- Exact diagonalisation and dynamics
- High-precision tensor network calculations
- Analytical scaling theory
