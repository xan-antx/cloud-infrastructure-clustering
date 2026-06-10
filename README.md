# Cloud Infrastructure Optimization Using K-Means Clustering

## Overview

This project applies unsupervised machine learning techniques to optimize cloud infrastructure resource allocation.

Using K-Means Clustering, cloud systems were grouped based on resource utilization metrics such as:

- CPU Usage
- Memory Usage
- Network Usage
- Disk I/O
- Energy Consumption
- Service Latency
- Predicted Workload

The objective was to identify workload tiers and provide insights for efficient cloud resource management.

---

## Dataset

Dataset Size:
- 6,345 records
- 10 features

Features include:

- CPU Usage (%)
- Memory Usage (MB)
- Network Usage (MBps)
- Disk I/O (MBps)
- Energy Consumption (Watts)
- Service Latency (ms)
- Predicted Workload (%)
- Workload Type
- Task Priority

---

## Methodology

### Data Preprocessing

- Missing value handling
- Outlier treatment
- Categorical encoding
- Feature scaling using StandardScaler

### Dimensionality Reduction

- PCA (Principal Component Analysis)

### Clustering

- K-Means Clustering

### Evaluation

- Elbow Method
- Silhouette Score

---

## Results

- Optimal Number of Clusters (K): 3
- Silhouette Score: 0.605
- Identified:
  - High-demand systems
  - Balanced systems
  - Low-demand systems

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

---

## Project Structure

cloud_resource_clustering.py

cloud_resource_allocation_dataset.csv

Cloud_Infrastructure_Clustering_Report.pdf

README.md

---

## Author

Anant Agrawal
