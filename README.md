This repository contains a complete workflow to analyze hyperspectral imaging data of corn samples and build machine learning models to predict DON (Deoxynivalenol) concentration—a key mycotoxin of concern in food safety.

The goal is to preprocess spectral data, reduce dimensionality for insights, and train & evaluate machine learning models including Feedforward Neural Network (FNN) and Convolutional Neural Network (CNN) to understand and predict DON levels.

**Project Overview**:
**Data Preprocessing**
Dropped irrelevant identifiers and handled missing values.

Normalized all spectral features using StandardScaler for stable model training.

Explored data patterns using spectral line plots and heatmaps.

**Dimensionality Reduction**
Applied PCA to retain 95% of data variance.

Visualized clusters using 2D and 3D scatter plots.

Supplemented with t-SNE to reveal local structure and separation based on DON levels.

**Modeling**
Trained two models:

FNN (Feedforward Neural Network): A simple dense architecture for baseline prediction.

CNN (1D Convolutional Neural Network): Exploits local spectral patterns and spatial continuity.

**Used MAE, RMSE, and R² for evaluation**:

FNN is better for minimizing individual prediction errors.
CNN is better for explaining variance and overall data structure.

