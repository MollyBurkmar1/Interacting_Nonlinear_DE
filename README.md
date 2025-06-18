# Dynamics of Dark Matter Interacting with Dark Energy with a Quadratic Equation of State

## Prerequisites

To run this notebook, the user requires a Mathematica license and to have installed MaTeX (see https://github.com/szhorvat/MaTeX).

To avoid a Git large file error, a Git hook has been added which clears the output when the file is committed. To set the hooks directory to the .githooks folder, the following command needs to be run in your local directory where you've pulled this repository: 

git config --local core.hooksPath .githooks/

## Analysis

The analysis in this notebook is used in the following paper: https://arxiv.org/abs/2504.01683

In this notebook, we analyse a system of ordinary differential equations describing pressureless dark matter interacting with dark energy with a quadratic equation of state. The aim of this analysis is to understand whether there are parameter ranges for which all trajectories in the phase space are non-singular, and have a decelerated period followed by a late-time acceleration during expansion.

The analysis in the notebook provides:

+ the fixed points of the full system with their eigenvalues and eigenvectors,
+ analysis of the parameter ranges which allow for a non-singular high energy repellor and low energy attractor in the phase space, 
+ analysis of the separatrix between the repellor and the singularity,
+ the phase spaces of the 2-D system describing the dark matter and dark energy,
+ the 3-D phase spaces, where the Hubble expansion function is included in the system of equations.
