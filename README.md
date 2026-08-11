This repository contains the research code for physics-informed neural networks (PINNs) developed to solve the incompressible Navier–Stokes equations across a wide range of Reynolds numbers, with applications to Lid-Driven Cavity Flow and Backward-Facing Step Flow.

Unlike conventional PINN approaches that train a separate model for a specific flow condition, the proposed framework is designed to learn a generalized solution across multiple Reynolds numbers. The repository includes implementations of parameterized and hybrid PINN approaches, sparse CFD supervision, and numerical experiments used to evaluate the generalization and predictive capability of the models.

The results generated using this code are reported in the following peer-reviewed publication:

“A. Jangir, R. Clements, R. Goyal, and G. Tabor, ‘Sparse-Supervised Hybrid Parameterized Physics-Informed Neural Networks for Incompressible Flows Across Reynolds Numbers,’ Physics of Fluids, 2026.”

DOI: 10.1063/5.0326675

Preprint: arXiv:2602.04670

The repository is intended to support reproducibility of the computational experiments and provide a foundation for further research in physics-informed machine learning, computational fluid dynamics, and data-efficient scientific computing.
