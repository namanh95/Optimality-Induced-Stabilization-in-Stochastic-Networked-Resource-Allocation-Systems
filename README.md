# Optimality-Induced-Stabilization-in-Stochastic-Networked-Resource-Allocation-Systems
Optimality-Induced-Stabilization/
│
├── generate_array_figures_2_to_7_table2_updated.py
│   Main script used to reproduce all numerical experiments and figures
│   appearing in the manuscript.
│
├── array_figures_final/
│   Output directory automatically created by the script.
│   Contains all generated figures used in the paper.
│
│   ├── figure2_drift_field.png
│   ├── figure3_network_topology_3d.png
│   ├── figure4_backlog_trajectories.png
│   ├── figure5_cost_vs_load.png
│   ├── figure6_phase_surface_3d.png
│   └── figure7_efficiency_frontier.png
│
├── README.md
│   Documentation describing the simulation framework,
│   dependencies, and instructions for reproducing results.
│
└── LICENSE (optional)
    Repository license file.
Mathematical Model:
The simulations study a stochastic networked resource allocation system in which multiple queues compete for shared service capacity. Arrivals follow a Markov-Modulated Poisson Process (MMPP), allowing the system to alternate between low- and high-demand regimes.
Optimality-Induced Stabilization Theorem (ODST)
The manuscript establishes the following principle. Optimality-Induced Stabilization Theorem
If the control policy minimizes a coercive convex stage cost, subject to the system constraints, then the resulting optimal policy generates a negative Foster–Lyapunov drift outside a compact set.
Key Insight
Traditional approaches such as Max-Weight scheduling enforce stability explicitly through queue-based prioritization. The ODST result demonstrates that stability can also arise endogenously from optimal cost minimization when the cost structure is sufficiently coercive. Thus, optimality itself induces stabilization.
