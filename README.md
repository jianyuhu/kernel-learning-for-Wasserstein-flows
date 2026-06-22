# Kernel Learning for Wasserstein Geometric Flows

This repository contains the implementation of the kernel learning framework for recovering energy functionals and interaction laws in Wasserstein geometric flows, together with the numerical experiments reported in the paper

#  Kernel Method for the Learning of Wasserstein Geometric Flows.

The code includes experiments on both Wasserstein gradient flows and Wasserstein Hamiltonian flows, as well as comparisons with sparse learning approaches based on local basis representations.

# Structure

* Wasserstein_Gradient_Flow/: numerical experiments for recovering interaction potentials in Wasserstein gradient flows.
* Wasserstein_Hamiltonian_Flow/: numerical experiments for recovering external potentials in Wasserstein Hamiltonian flows.
* Kernel_Method/: implementation of the proposed RKHS-based variational learning framework.
* Sparse_Learning/: sparse learning baselines using local basis expansions.
* Figures/: scripts and generated figures for reproducing the results reported in the paper.

# Requirements

The main dependencies are:

* numpy
* scipy
* matplotlib
* scikit-learn
* pandas
* tqdm

# Reproducing the Experiments

To reproduce the numerical results, run the corresponding scripts in each experiment directory. The generated figures and error tables should closely match those reported in the paper.
