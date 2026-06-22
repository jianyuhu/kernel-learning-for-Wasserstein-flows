## Kernel Learning for Wasserstein Geometric Flows

Official implementation of the numerical experiments reported in the paper “A Kernel Method for the Learning of Wasserstein Geometric Flows”.

This repository contains the implementation of the proposed RKHS-based kernel learning framework for recovering interaction laws and energy functionals in Wasserstein geometric flows.

The code includes experiments on:

* Wasserstein gradient flows
* Wasserstein Hamiltonian flows
* Flux-based variational formulations
* $A^\delta$-based variational formulations
* Sparse learning methods based on local basis representations


# Repository Structure

Wasserstein gradient flow

Numerical experiments for recovering interaction potentials in Wasserstein gradient flows.

Wasserstein gradient flow/
├── data_generation.ipynb
├── ex1_kernel_Adelta.ipynb
├── ex1_kernel_flux.ipynb
├── ex1_sparse.ipynb
├── ex2_kernel_Adelta.ipynb
├── ex2_kernel_flux.ipynb
├── ex2_sparse.ipynb
├── figures_data/
├── figures_kernel_Adelta/
├── figures_kernel_flux/
├── figures_sparse/
└── data/

Wasserstein Hamiltonian flow

Numerical experiments for recovering external potentials in Wasserstein Hamiltonian flows.

Wasserstein Hamiltonian flow/
├── data_generation.ipynb
├── ex3_4_kernel.ipynb
├── ex3_4_sparse.ipynb
├── figures/
├── figures_highly_nonconvex/
├── figures_polynomial/
└── data/


# Requirements

The main dependencies are:

numpy
scipy
matplotlib
pandas
scikit-learn
jupyter
tqdm


# Running the Experiments

Wasserstein Gradient Flow

1. Generate the training data:

data_generation.ipynb

2. Run the corresponding notebooks:

ex1_kernel_Adelta.ipynb
ex1_kernel_flux.ipynb
ex1_sparse.ipynb
ex2_kernel_Adelta.ipynb
ex2_kernel_flux.ipynb
ex2_sparse.ipynb

Wasserstein Hamiltonian Flow

1. Generate the training data:

data_generation.ipynb

2. Run:

ex3_4_kernel.ipynb
ex3_4_sparse.ipynb


# Numerical Experiments

The repository reproduces all numerical experiments presented in the paper, including:

* Recovery of compactly supported interaction kernels
* Comparison between flux-based and $A^\delta$-based formulations
* Recovery under coarse spatio-temporal observations
* Sparse learning baselines with local basis representations
* Recovery of external potentials in Wasserstein Hamiltonian flows
* Highly non-convex and polynomial potential examples

