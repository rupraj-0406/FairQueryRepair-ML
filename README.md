# FairQueryRepair-ML

Machine Learning Guided Fair Query Repair with Cross-Dataset Adaptation.

## Overview

This project extends a fairness-aware query repair framework by introducing machine learning techniques for repair prediction and ML-guided search.

### Contributions

* Rule-based fairness repair reproduction
* Machine learning repair prediction
* Hard-query handling through guided search
* Cross-dataset adaptation from Adult to COMPAS

## Results

| Method           | Success Rate |
| ---------------- | ------------ |
| Pure ML Repair   | 28%          |
| ML-Guided Search | 87%          |

## Cross-Dataset Adaptation

The framework was successfully adapted from the Adult dataset to the COMPAS dataset.

Average SPD Reduction:

* Adult: 0.248 → 0.175
* COMPAS: 0.191 → 0.113

## Repository Structure

* `datasets/` - Training and repair datasets
* `figures/` - Experimental plots and visualizations
* `notebooks/` - Research notebooks
* `results/` - Experimental results
* `paper/` - Manuscript and presentation materials
