# Customer Segmentation with Unsupervised Learning

## Course Overview
This project is part of **CSCA 5632: Introduction to Machine Learning: Unsupervised Learning**, a course offered by CU Boulder.
- Theoretical and practical foundations of unsupervised learning using Python and Jupyter Notebook.
- Machine learning models such as K-Means Clustering, DBSCAN, Hierarchical Clustering, and Principal Component Analysis (PCA).

### Key Learning Outcomes:
- Proficient use of clustering algorithms and dimensionality reduction techniques.
- Understanding how to interpret and visualize clustering results.
- Ability to compare and evaluate the effectiveness of different unsupervised learning models.
- Experience with real-world data preprocessing and feature scaling.

## Project Summary
**Objective:**
Develop an unsupervised learning model to segment customers based on their purchasing behaviors, enabling businesses to tailor marketing strategies for different customer groups.

**Significance:**
Understanding customer segments helps businesses personalize services, improve marketing efficiency, and enhance customer satisfaction. Unsupervised learning methods offer powerful tools for discovering hidden patterns in customer data without needing labeled outcomes.

## Project Components

### Introduction
The project focuses on identifying meaningful customer segments using clustering techniques. By analyzing customer data, the project uncovers patterns that can guide business strategies and decision-making.

### Methodology
1. **Data Preparation:**
   - Data cleaning to handle missing values and inconsistencies.
   - Feature scaling using StandardScaler for uniformity across variables.

2. **Model Development:**
   - Several clustering techniques were implemented, including:
     - K-Means Clustering
     - DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
     - Hierarchical Clustering
   - Dimensionality reduction via Principal Component Analysis (PCA) for improved visualization and interpretation.

3. **Evaluation Metrics:**
   - Silhouette Score and Davies-Bouldin Index were used to assess clustering quality.
   - Visualizations such as dendrograms and cluster scatter plots provided insights into the structure and separability of clusters.

### Conclusion
The project demonstrated the effectiveness of unsupervised learning techniques for uncovering customer segments. Proper clustering can help businesses enhance targeting, increase customer engagement, and drive better business outcomes.

## Models Used
- **K-Means Clustering:** Partitioned data into distinct groups based on similarity.
- **DBSCAN:** Identified clusters of varying shapes and handled outliers effectively.
- **Hierarchical Clustering:** Built a hierarchy of clusters for flexible segmentation.
- **PCA (Principal Component Analysis):** Reduced data dimensionality while preserving variance for visualization.

## Acknowledgments
I would like to thank **Dr. Geena Kim**, the instructor for CSCA 5632, for her guidance throughout the course. The theoretical concepts and practical exercises from the course were instrumental in completing this project.

## Future Work
- Experiment with alternative distance metrics and clustering algorithms like Gaussian Mixture Models.
- Incorporate additional customer features such as behavioral and demographic attributes.
- Deploy the segmentation model within a marketing platform to automate targeted campaigns.

## Repository Contents
- **Notebooks:** Jupyter notebooks containing data preprocessing, clustering analysis, and visualizations.
- **Reports:** Detailed analysis of cluster structures and evaluation metrics.
- **Datasets:** The dataset was sourced from [https://www.kaggle.com/datasets/yasserh/loan-default-dataset/data](https://www.kaggle.com/datasets/yasserh/loan-default-dataset/data).