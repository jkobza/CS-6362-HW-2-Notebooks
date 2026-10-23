# CS 6362 — Assignment 2 Reproductions

Independent PyTorch reproductions of three figures for **Advanced Machine Learning (Fall 2026)**.

| Paper | Figure | Notebook | Recommended GPU |
|---|---|---|---|
| Zhang et al. (2017) | Figure 1(a–c) | [Zhang reproduction](Zhang_Figure1_Independent_Reproduction-2.ipynb) | Colab A100 |
| Keskar et al. (2017) | Figure 3 (F1, C1, C2) | [Keskar reproduction](keskar-figure3-kaggle-2xt4-full.ipynb) | Kaggle 2×T4 |
| Higgins et al. (2017) | Figure 7A–B | [β-VAE reproduction](Higgins_Figure7_Independent_BetaVAE-2.ipynb) | Colab A100 |

## How to run

Open a notebook in its recommended environment, enable the GPU, and **Run All**. Setup cells install/import dependencies and download CIFAR-10, MNIST, or dSprites as needed. Each notebook trains models and generates its figures from measured results. No pretrained weights are required.
