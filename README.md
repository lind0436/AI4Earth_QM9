# AI4Earth: Molecular Property Prediction with QM9 & PyTorch Geometric
Notebooks and supporting files for the University of Minnesota's [AI4Earth Summer Program](https://cse.umn.edu/cs/ai-earth-program)

This repository contains Jupyter Notebooks demonstrating Graph Neural Networks (GNNs) and deep learning workflows for molecular property prediction using the **QM9 dataset** via the **PyTorch Geometric (PyG)** library.
The QM9 dataset is from the paper: [MoleculeNet: A Benchmark for Molecular Machine Learning](https://arxiv.org/abs/1703.00564).

---

## 🌌 Overview of the QM9 Dataset

The **QM9 dataset** is a cornerstone benchmark in molecular machine learning and quantum chemistry. It contains geometric, energetic, electronic, and thermodynamic properties for approximately **130,000 small organic molecules** with up to 9 heavy atoms (C, O, N, F, excluding H). 

All properties were computed using Density Functional Theory (DFT) at the `B3LYP/6-31G(2df,p)` level of quantum chemical theory.

### Dataset Statistics (PyG Implementation)
| Metric | Value |
| :--- | :--- |
| **Number of Graphs (Molecules)** | 130,831 |
| **Average Nodes (Atoms) per Graph** | ~18.0 |
| **Average Edges (Bonds) per Graph** | ~37.3 |
| **Node Features** | 11 |
| **Regression Targets (Tasks)** | 19 |

For best results, work through the notebooks in order, beginning with [Part_0_using_QM9.ipynb](Part_0_using_QM9.ipynb)
