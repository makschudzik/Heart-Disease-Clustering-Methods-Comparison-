# Heart-Disease-Clustering-Methods-Comparison-

This project explores different clustering algorithms to identify meaningful patterns in the heart disease dataset. It includes data preprocessing, dimensionality reduction, and model evaluation to determine the most effective clustering method.

## 🚀 Project Overview
This notebook covers the following steps:
1. **Data Cleaning and Preprocessing** - Removing duplicates, handling missing values, and scaling the data.
2. **Dimensionality Reduction** - Using PCA to reduce data complexity while retaining critical features.
3. **Model Training and Clustering** - Testing multiple clustering algorithms including KMeans, MeanShift, Gaussian Mixture, and K-Neighbors.
4. **Evaluation** - Comparing models using the Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Score.
5. **Visualization** - Generating informative plots to visualize clustering effectiveness.

## 📊 Results
Initial analysis shows that **KMeans** provides the best clustering performance based on the chosen evaluation metrics. This suggests that the heart disease data can be effectively grouped using this approach.

To set up this project locally, clone the repository and install the required dependencies:
```bash
git clone https://github.com/YourUsername/Heart-Disease-Clustering.git
cd Heart-Disease-Clustering
pip install -r requirements.txt
