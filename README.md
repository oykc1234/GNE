# Graph Neural Evolution (GNE)

Official implementation of **"Learn from Global Correlations: Enhancing Evolutionary Algorithm via Spectral GNN"** - Accepted as Poster at AAAI 2026.

## 📝 Abstract

Evolutionary algorithms (EAs) are optimization algorithms that simulate natural selection and genetic mechanisms. Despite advancements, existing EAs have two main issues: (1) they rarely update next-generation individuals based on global correlations, thus limiting comprehensive learning; (2) it is challenging to balance exploration and exploitation, where excessive exploitation leads to premature convergence to local optima, while excessive exploration results in an excessively slow search.

To address these challenges, we propose a novel evolutionary algorithm framework called **Graph Neural Evolution (GNE)**. Unlike traditional EAs, GNE represents the population as a graph, where nodes correspond to individuals, and edges capture their relationships, thus effectively leveraging global information. Meanwhile, GNE utilizes spectral graph neural networks (GNNs) to decompose evolutionary signals into their frequency components and designs a filtering function to fuse these components. High-frequency components capture diverse global information, while low-frequency components capture more consistent information.

## 🎯 Key Features

- **Graph-based Population Representation**: Models individuals as nodes and their relationships as edges
- **Spectral Graph Neural Networks**: Decomposes evolutionary signals into frequency components
- **Adaptive Filtering**: Explicit frequency filtering strategy for better exploration-exploitation balance
- **Interpretable Control**: Direct manipulation of global-scale features through frequency components
- **Parameter-free Design**: Reduces reliance on manual parameter tuning

## 🏆 Performance

Extensive evaluations on nine benchmark functions (Sphere, Rastrigin, Rosenbrock, etc.) demonstrate that GNE consistently outperforms both classical algorithms (GA, DE, CMA-ES) and advanced algorithms (SDAES, RL-SHADE) under various conditions:

- **Original scenarios**
- **Noise-corrupted scenarios** 
- **Optimal solution deviation scenarios**

GNE achieves solution quality several orders of magnitude better than other algorithms (e.g., 3.07e-20 mean on Sphere vs. 1.51e-07).

## 📚 Benchmark Functions

The code includes implementations of 9 classic optimization functions:

| Function | Name | Characteristics |
|----------|------|-----------------|
| F1 | Sphere | Unimodal, convex, symmetric |
| F2 | Schwefel | Unimodal, non-convex |
| F3 | Schwefel 2.22 | Unimodal, non-differentiable |
| F4 | Schwefel 2.26 | Multimodal, non-convex |
| F5 | Rosenbrock | Unimodal, valley-shaped |
| F6 | Quartic | Unimodal with noise |
| F7 | Rastrigin | Highly multimodal |
| F8 | Ackley | Multimodal with flat regions |
| F9 | Levy | Multimodal, non-convex |


