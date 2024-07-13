## Finding and exploring promising search space for The 0–1 Multidimensional Knapsack Problem (FEPSS)

 This repository contains the code used for the experiments in the paper "Finding and exploring promising search space for The 0–1 Multidimensional Knapsack Problem". (https://authors.elsevier.com/c/1jQFp5aecSvMEl)

 The 0–1, Multidimensional Knapsack Problem (MKP) is a classical NP-hard combinatorial optimization problem with many engineering applications. In this paper, we propose a novel algorithm combining evolutionary computation with the exact algorithm to solve the 0–1 MKP. It maintains a set of solutions and utilizes the information from the population to extract good partial assignments. To find high-quality solutions, an exact algorithm is applied to explore the promising search space specified by the good partial assignments. The new solutions are used to update the population. Thus, the good partial assignments evolve towards a better direction with the improvement of the population. Extensive experimentation with commonly used benchmark sets shows that our algorithm outperforms the state-of-the-art heuristic algorithms, TPTEA and DQPSO, as well as the commercial solver CPlex. It finds better solutions than the existing algorithms and provides new lower bounds for 10 large and hard instances.

 ### Paper

    @article{XU2024111934,
title = {Finding and exploring promising search space for The 0–1 Multidimensional Knapsack Problem},
journal = {Applied Soft Computing},
volume = {164},
pages = {111934},
year = {2024},
issn = {1568-4946},
doi = {https://doi.org/10.1016/j.asoc.2024.111934},
url = {https://www.sciencedirect.com/science/article/pii/S1568494624007087},
author = {Jitao Xu and Hongbo Li and Minghao Yin},
keywords = {0–1 Multidimensional Knapsack Problem, Evolutionary computation, Heuristic, Exact algorithm, Large Neighborhood Search},
abstract = {The 0–1, Multidimensional Knapsack Problem (MKP) is a classical NP-hard combinatorial optimization problem with many engineering applications. In this paper, we propose a novel algorithm combining evolutionary computation with the exact algorithm to solve the 0–1 MKP. It maintains a set of solutions and utilizes the information from the population to extract good partial assignments. To find high-quality solutions, an exact algorithm is applied to explore the promising search space specified by the good partial assignments. The new solutions are used to update the population. Thus, the good partial assignments evolve towards a better direction with the improvement of the population. Extensive experimentation with commonly used benchmark sets shows that our algorithm outperforms the state-of-the-art heuristic algorithms, TPTEA and DQPSO, as well as the commercial solver CPlex. It finds better solutions than the existing algorithms and provides new lower bounds for 10 large and hard instances.}
}