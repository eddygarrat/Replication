## Table of Contents

- [An abstract toy model for replication](#an-abstract-toy-model-for-replication)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
   - [Interactions Overview-Hamiltonian](#interactions-overview-hamiltonian)

  - [Soft Res](#soft-res)

## An abstract toy model for replication

## Table of Contents

## Introduction
Self replication is an attribute of any system to duplicate and produce an identical copy. I try to build an Ising based lattice model for replication inspired by Michael Brenner's colloidal cluster replication simulation setup.  
Below you’ll see:

- An overview of the model  
- A few results  

## Interactions Overview-Hamiltonian
We use a 2D grid of spins with a fixed spin structure at a specified position in the grid. The Hamiltonian for
this system is the well-known 2D Ising Hamiltonian, with three types of interactions involved:  
(i) interaction of spins part of the fixed structure,  
(ii) interaction between two dynamic spins, and  
(iii) interaction between spins part of the fixed structure and a dynamic spin.  

From hereforth, a dynamic spin is labelled as ‘D’ and a fixed spin as ‘F’. (Dynamic spins flip constantly, fixed spins do not flip.)  

The Ising Hamiltonian:  
$$
H = \sum_{\langle i,j \rangle} J_{ij} S_i S_j
$$
## Soft Res
While plotting the number of fixed structures (ns) against the monte carlo steps(MCstep) , it could be seen
that with allostery there has been an exponential growth. The growth over montecarlo steps in the case of
no allostery saturates after very large number of montecarlo steps

 
