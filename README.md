# McKean_PathDep
Examples of simulation of path-dependent McKean-Vlasov equations.

This project presents the implementation of the simulations from [Bernou-Liu, Particle method for the numerical simulation of the
path-dependent McKean-Vlasov equation, 2024]. Several datasets obtained from those codes are also included. 

Composition:
  - Simulation_Path_Dependent_OU(1).ipynb contains the code of our simulation of a modified Ornstein-Uhlenbeck process with path-dependency;
  - Intrinsic_excitability_Final.ipynb contains the code of our simulation of a neural mass model with potentiation effects;
  - The numerical errors associated to the convergence in Wasserstein distance for the OU process are contained in files error_final_OU_M100, error_final_OU_M2000 and error_final_OU_MN55;
  - The numerical errors associated to the convergence in Wasserstein distance for individual coordinates of the Neural Mass model are contained in error_final_Neural_Wasserstein;
  - The numerical errors associated to the convergence in Wasserstein distance estimated through test functions of the Neural Mass model are contained in error_final_Neural_Wasserstein.

Files containing particle simulations are available on Zenodo, https://zenodo.org/doi/10.5281/zenodo.11656117
