# Heterogeneous Graph Neural Networks (HGNN)

> Research workspace for **Heterogeneous Graph Neural Networks (HGNNs)** and relation-aware learning on structured data.

## Overview

This repository explores graph learning when a problem contains multiple types of nodes, edges, and relations. The goal is to understand when heterogeneous representations provide useful information beyond a standard homogeneous Graph Neural Network (GNN).

## Research Questions

- How should heterogeneous entities and relations be represented?
- When does relation-aware message passing improve over homogeneous GNN baselines?
- Which graph architectures are suitable for network-intelligence and biomedical graph problems?
- How can experiments be made reproducible and comparable?

## Potential Applications

- **Telecom & network intelligence:** multi-relational network topology and KPI graphs.
- **Complex networks:** heterogeneous entities and interactions.
- **Biomedical AI:** brain and physiological networks.
- **Recommendation and relational learning:** multi-type user/item/entity graphs.

## Current Status

**Early research / prototype stage.** This repository is a research foundation, not a finished benchmark framework. Results should be considered exploratory until they are backed by reproducible experiments.

## Planned Research Pipeline

```text
Raw / Structured Data
        ↓
Heterogeneous Graph Schema
        ↓
Feature & Relation Construction
        ↓
Homogeneous GNN Baseline
        ↓
HGNN Models
        ↓
Evaluation & Ablation
        ↓
Analysis / Visualization
```

## Roadmap

- [ ] Formalize reusable heterogeneous graph schemas.
- [ ] Implement reproducible GNN/HGNN baselines.
- [ ] Add dataset preparation and validation utilities.
- [ ] Define consistent train/validation/test protocols.
- [ ] Compare homogeneous and heterogeneous message passing.
- [ ] Add ablation studies and experiment tracking.
- [ ] Investigate telecom and biomedical use cases.

## Engineering Principles

The project follows modular implementation, explicit experiment configuration, testing, reproducibility, and a strict separation between **verified results** and future hypotheses.

## Technology

`Python` · `PyTorch` · `PyTorch Geometric` · `GNN` · `HGNN` · `Graph Learning`

## Author

**Mohammad Mahdi Shafighi** — M.Sc. Artificial Intelligence

Research interests: Network Intelligence · Reinforcement Learning · Graph Learning · Applied AI