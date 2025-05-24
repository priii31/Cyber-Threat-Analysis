# Cyber Threat Analysis using Machine Learning

This repository contains a complete machine learning pipeline for analyzing and predicting patterns in cyber threat data.


## Overview

Cybersecurity is a growing concern worldwide. This project aims to:
- Analyze cyber threat incidents across countries, industries, and years.
- Use ML models to predict financial losses or classify attack types.
- Cluster similar incidents to find hidden patterns.


## Dataset

Sample features in the dataset:
- *Country*
- *Year*
- *Attack Type*
- *Target Industry*
- *Financial Loss (in Million $)*
- *Number of Affected Users*
- *Attack Source*
- *Security Vulnerability*
- *Type*
- *Defense Mechanism Used*
- *Incident Resolution Time (in Hours)*


## Features

### Data Processing
- Null value handling
- Label Encoding of categorical variables
- Feature scaling for algorithms that require it

### Visualizations
- Correlation heatmaps
- Seaborn pairplots
- Cluster scatterplots

### Models Implemented
- *Regression*: Linear Regression, Random Forest, KNN
- *Classification*: Decision Tree
- *Clustering*: K-Means

---

## Getting Started

### Dependencies

bash
pip install pandas numpy matplotlib seaborn scikit-learn


### How to Use

1. Upload your dataset (CSV) in the notebook.
2. Run preprocessing and visualizations.
3. Train and evaluate models.
4. Interpret results and export predictions if needed.

---

## Output

- Plots for trend analysis
- Performance metrics (MSE, RÂ², Accuracy)
- Cluster labels for each data point

---

## Author

*Priyal Choudhary*  
Email: priyalchoudhary41@gmail.com
