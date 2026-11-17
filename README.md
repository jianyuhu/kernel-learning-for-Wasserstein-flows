# Kernel Learning for Wasserstein Geometric Flows

Code accompanying the paper “A Kernel Method for the Learning of Wasserstein Geometric Flows”.

This repository implements an RKHS-based learning framework for recovering external and interaction potentials in Wasserstein gradient and Hamiltonian flows.

## Experiments in the Revised Manuscript

The notebooks in `New experiments/` correspond to Examples 1–4 of the revised manuscript. Both potentials are treated as unknown in all four examples.

| Notebook | Experiment |
| --- | --- |
| `Example 1.ipynb` | Joint recovery in a one-dimensional Wasserstein gradient flow |
| `Example 2.ipynb` | A nonstationary gradient-flow trajectory with an unobservable interaction component |
| `Example 3.ipynb` | Joint recovery in a two-dimensional Wasserstein Hamiltonian flow |
| `Example 4.ipynb` | A nonstationary Hamiltonian trajectory with unobservable interaction components |

Examples 1–2 use density observations. Examples 3–4 use observations of both the density and the velocity potential.

The experiments report potential reconstruction errors separately from observation-equation residuals.

## Repository Structure

- `New experiments/`: Examples 1–4 of the revised manuscript.
- `Wasserstein gradient flow/`: Experiments from the previous manuscript version, including interaction-potential recovery, flux-based and A-delta-based formulations, and sparse-learning comparisons.
- `Wasserstein Hamiltonian flow/`: External-potential recovery and sparse-learning experiments from the previous manuscript version.

The original experiment folders are retained for reference. Their example numbering refers to the previous manuscript version.

## Requirements

The main dependencies are:

- numpy
- scipy
- matplotlib
- pandas
- scikit-learn
- jupyter
- tqdm

## Running the Experiments

### Revised Manuscript

Open the corresponding notebook in `New experiments/` and follow its instructions.

### Previous Manuscript Version

For the original gradient-flow experiments, first run `data_generation.ipynb` in `Wasserstein gradient flow/`, then run the desired notebook:

- `ex1_kernel_Adelta.ipynb`
- `ex1_kernel_flux.ipynb`
- `ex1_sparse.ipynb`
- `ex2_kernel_Adelta.ipynb`
- `ex2_kernel_flux.ipynb`
- `ex2_sparse.ipynb`

For the original Hamiltonian-flow experiments, first run `data_generation.ipynb` in `Wasserstein Hamiltonian flow/`, then run:

- `ex3_4_kernel.ipynb`
- `ex3_4_sparse.ipynb`
