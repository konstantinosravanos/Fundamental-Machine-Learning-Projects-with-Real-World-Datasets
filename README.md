# Fundamental-Machine-Learning-Projects-with-Real-World-Datasets


This repository contains three Jupyter Notebooks showcasing fundamental machine learning techniques using real-world datasets. Each notebook represents a distinct ML task: classification, regression, and clustering.

## Table of Contents

- [Overview](#overview)
- [Notebooks](#notebooks)
  - [1. Classification](#1-classification)
  - [2. Regression](#2-regression)
  - [3. Clustering](#3-clustering)
- [Datasets](#datasets)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

---

## Overview

The purpose of this repository is to provide an introductory-level application of supervised and unsupervised machine learning techniques. The projects are implemented in Python using libraries such as `pandas`, `scikit-learn`, `matplotlib`, and `seaborn`.

## Notebooks

### 1. Classification

- **Notebook**: `classification.ipynb`
- **Objective**: Predict student performance based on demographic and academic features.
- **Techniques**: Data preprocessing, label encoding, decision trees, evaluation metrics.
- **Dataset**: `student-por.csv` (Portuguese student data).

### 2. Regression

- **Notebook**: `regression.ipynb`
- **Objective**: Predict housing prices in New York.
- **Techniques**: Linear Regression, feature selection, residual analysis.
- **Dataset**: `NY-House-Dataset.csv`

### 3. Clustering

- **Notebook**: `clustering.ipynb`
- **Objective**: Segment customers based on marketing campaign data.
- **Techniques**: K-Means clustering, data scaling, silhouette score.
- **Dataset**: `marketing_campaign.csv`

## Datasets

All datasets are publicly available and used strictly for educational purposes:

- `student-por.csv`: Student performance data from UCI ML Repository.
- `NY-House-Dataset.csv`: A housing dataset with NYC property features.
- `marketing_campaign.csv`: Contains anonymized customer data from a marketing campaign.

## Requirements

To run the notebooks, install the following packages (you can use a virtual environment):

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
