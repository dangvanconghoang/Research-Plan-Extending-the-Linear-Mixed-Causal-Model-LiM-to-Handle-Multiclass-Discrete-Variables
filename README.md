# Extending the Linear Mixed Causal Model (LiM) to Handle Multiclass Discrete Variables

## Overview

This repository contains the source code and supplementary materials for the research project:

**"Extending the Linear Mixed Causal Model to Handle Multiclass Discrete Variables"**

This project extends the **LiM (Linear Mixed Causal Model)** — originally designed for continuous and binary variables — to support **multiclass discrete variables** using **multinomial logistic regression**, enabling causal discovery in more realistic mixed-type datasets.

The extension is motivated by the need to analyze real-world data in economics, sociology, and policy analysis, where categorical variables with multiple levels (e.g., occupation, education) are common.

---

## Key Features

- Extension of LiM model to handle discrete variables with >2 categories.
- Proof-of-concept identifiability analysis in bivariate cases (continuous + multiclass).
- Python implementation of the extended two-step hybrid causal discovery algorithm.
- Synthetic data generation and evaluation.
- Benchmarks against:
  - PC Algorithm
  - Standard LiNGAM
  - L-LiNGAM
- Evaluation using:
  - F1 Score
  - False Discovery Rate (FDR)
  - Structural Hamming Distance (SHD)
