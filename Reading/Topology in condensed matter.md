---
Title: Topology in Condensed Matter
Type: Website
Status: Reading
Author: [Anton Akhmerov (TU Delft), Jay Sau (University of Maryland), Bernard van Heck (Leiden University), Sebastian Rubbert (TU Delft), Rafał Skolasiński (TU Delft), Bas Nijholt (TU Delft), Irfan Muhammad (TU Delft), Tómas Örn Rosdahl (TU Delft)]
Stars: ⭐⭐⭐⭐⭐
url: https://topocondmat.org/index.html
File: 
aliases: 
tags: 
---

# Hamiltonians, Topology, and Symmetry

## Topology and Symmetry

## Zero-dimensional Quantum System

## Topology and Gapped Quantum System

## The Concept of a Topological Invariant

### Role of Conservation Laws

## Time-reversal Symmetry

## Sublattice Symmetry

Let's now take a system where we can split all the degrees of freedom into two groups (say group AAA and group BBB) such that the Hamiltonian only has nonzero matrix elements between two groups, and not inside each group. This situation arises naturally when the lattice has two sublattices, as in the hexagonal carbon lattice of graphene. So let's imagine our quantum dot is now a graphene dot:

![](https://secure2.wostatic.cn/static/uTXPvmZQavYrD7Tw9mx4Kj/graphene_dot.svg)

Because of the sublattice symmetry, the Hamiltonian of the graphene dot is in the form:

H=(0HABHAB†0)H = \left( \begin{array}{ccc} 0& H_{AB}\\ H_{AB}^\dagger& 0\\ \end{array} \right) H=​⎝​⎛​​​0​H​AB​†​​​​​​H​AB​​​0​​​⎠​⎞​​

If we introduce a diagonal matrix σz=(IA00−IB)\sigma_z=\left( \begin{array}{} I_A & 0\\ 0 & -I_B \end{array} \right)σ​z​​=(​I​A​​​0​​​0​−I​B​​​​), then we have

so the sublattice symmetry of the Hamiltonian becomes σzHσz=−H\sigma_z H \sigma_z = -Hσ​z​​Hσ​z​​=−H.

Then if (ψA,ψB)T(\psi_A, \psi_B)^T(ψ​A​​,ψ​B​​)​T​​ is an eigenvector of HHH with eigenvalue ε\varepsilonε, (ψA,−ψB)T(\psi_A, -\psi_B)^T(ψ​A​​,−ψ​B​​)​T​​ is an eigenvector with eigenvalue −ε-\varepsilon−ε (see as below).

\begin{align*} H(\psi_A,\psi_B)^T &= \varepsilon (\psi_A,\psi_B)^T \\ \sigma_z H(\psi_A,\psi_B)^T &= \sigma_z \varepsilon (\psi_A,\psi_B)^T \\ -H\sigma_z (\psi_A,\psi_B)^T &= \varepsilon (\psi_A,-\psi_B)^T\\ H(\psi_A,-\psi_B)^T &= -\varepsilon (\psi_A,-\psi_B)^T \end{align*}

From this conclusion, we can say that

-   **a symmetric spectrum is the consequence of sublattice symmetry**
-   there is not one single level to cross zero energy
-   we can deform the Hamiltonian with sublattice symmetry into another without closing the gap

## Particle-hole Symmetry

This symmetry shows up in superconducting systems.

A superconductor will create and annihilate pairs of electrons by breaking apart and forming [Cooper pair - Wikipedia](https://en.wikipedia.org/wiki/Cooper_pair). This results in a Hamiltanian

H=∑nmHnmcn†cm+12(Δnmcn†cm†+Δnm∗cmcn)\mathcal{H} = \sum_{nm}{H_{nm}c_n^\dagger c_m + \frac{1}{2}\left(\Delta_{nm}c_n^\dagger c_m^\dagger + \Delta_{nm}^*c_m c_n \right)} H=​nm​∑​​H​nm​​c​n​†​​c​m​​+​2​​1​​(Δ​nm​​c​n​†​​c​m​†​​+Δ​nm​∗​​c​m​​c​n​​)