# Importance sampling for a robust and efficient multilevel Monte Carlo estimator for stochastic reaction networks


This repository includes Matlab codes/routines that were used in my Bachelor thesis entitled "Numerical Methods For Uncertainty Quantification In Option Pricing" that can be found in: https://www.researchgate.net/publication/330005261_Numerical_Methods_For_Uncertainty_Quantification_In_Option_Pricing. This work intends to design a more efficient and robust multilevel Monte Carlo (MLMC) estimator for stochastic biological systems and pure jumps. In particular, we address the issue of catastrophic coupling, explained in https://arxiv.org/abs/1911.06286.

The repository includes:

1- Folder “MLMC_without_IS_for_SRNs” includes all related code to MLMC, based on explicit tau-leap, without importance sampling

2- Folder “MLMC_with_IS_for_SRNs” includes all related code to MLMC, based on explicit tau-leap, with importance sampling.

3- Folder “MC_SSA_SRNs” includes all related code to Monte Carlo (MC) with an exact scheme SSA.

4- Folder “Produced_results” includes all obtained results in our manuscript.
