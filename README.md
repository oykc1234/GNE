Graph Neural Evolution (GNE) - Code Repository
Overview
This repository will host the code for Graph Neural Evolution (GNE), a novel evolutionary algorithm (EA) inspired by the intrinsic duality between Graph Neural Networks (GNNs) and EAs. The concept bridges two traditionally distinct fields, proposing a method that models individuals as nodes in a graph while incorporating frequency-domain filters to enhance global exploration and local exploitation. GNE aggregates both high-frequency (diversity-enhancing) and low-frequency (stability-promoting) information, transforming evolutionary algorithms into interpretable and tunable mechanisms in the frequency domain.

Through extensive experimentation on benchmark functions, GNE has shown superior performance over state-of-the-art algorithms, including GA, DE, CMA-ES, SDAES, and RL-SHADE. It demonstrates robustness, adaptability, and outstanding convergence in complex landscapes, optimal solution shifts, and noisy environments.

Planned Features
Graph Neural Evolution (GNE) Algorithm: Full implementation of the GNE algorithm.
Benchmark Tests: Evaluate GNE on various benchmark functions to demonstrate its superiority.
Custom Frequency Domain Filters: Integrate filters that balance diversity and stability in optimization.
Task-Adaptive Filters: Implement and test task-specific filters for optimization and machine learning.
Hybrid Approaches: Explore the potential of hybrid algorithms combining evolutionary strategies and GNN insights.
Paper Details
This code corresponds to our paper titled "Graph Neural Networks Are Evolutionary Algorithms", which can be accessed through the following link:
Graph Neural Networks Are Evolutionary Algorithms

The paper provides a conceptual and mathematical foundation linking evolutionary algorithms and graph neural networks, encouraging the development of new task-adaptive filters and hybrid optimization strategies. Additionally, GNE’s insights have the potential to advance global information propagation and mitigate oversmoothing in GNNs.

Future Plans
We plan to release the implementation of the GNE algorithm in this repository soon. The code will demonstrate how GNE outperforms other state-of-the-art evolutionary algorithms, and it will offer a foundation for interdisciplinary innovation in optimization problems and machine learning tasks. In the future, this repository will include:

Full source code for the GNE algorithm.
Detailed documentation on how to use the code and replicate the experiments described in the paper.
Examples for applying GNE to real-world optimization problems.
Contributions and ideas for further enhancements are welcome!
Contact Information
For questions, suggestions, or collaborations, feel free to reach out to the authors:

Kaichen Ouyang (Department of Mathematics, University of Science and Technology of China)
Email: oykc@mail.ustc.edu.cn

Shengwei Fu (Key Laboratory of Advanced Manufacturing Technology, Guizhou University)
Email: shengwei_fu@163.com
