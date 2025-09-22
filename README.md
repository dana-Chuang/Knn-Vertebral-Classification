# Vertebral Column Classification with KNN  

This project implements a **K-Nearest Neighbors (KNN)** classifier to distinguish between **normal** and **abnormal** spine conditions using the [UCI Vertebral Column dataset](https://archive.ics.uci.edu/ml/datasets/Vertebral+Column).  

The goal is to explore how distance metrics, training set size, and weighted voting affect the performance of non-parametric models.  

---

## Features
- **Exploratory Data Analysis**: scatterplots & boxplots for Normal vs. Abnormal classes.  
- **KNN Variants**: tested Euclidean, Manhattan, Chebyshev, Minkowski, and Mahalanobis distances.  
- **Weighted KNN**: applied distance-based voting for improved decision boundaries.  
- **Learning Curves**: examined the effect of training set size on test performance.  
- **Model Evaluation**: confusion matrix, precision, recall, F1-score, error rate plots.  