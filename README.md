**Unsupervised Clustering of Cryptocurrencies**

This project utilizes unsupervised machine learning techniques to analyze cryptocurrency market data. By applying K-Means clustering and Principal Component Analysis (PCA), the goal is to categorize cryptocurrencies based on their market behaviors, identify optimal cluster numbers, and visualize the results for better insights.

**Project Overview**

The repository contains the following key components:

Crypto_Clustering.ipynb: A Jupyter notebook that implements the clustering analysis.

crypto_market_data.csv: A dataset containing historical market data of various cryptocurrencies.

🔍 Techniques Used
1. K-Means Clustering is employed to group cryptocurrencies into clusters based on their market data.

2. Principal Component Analysis (PCA) is applied to reduce the dimensionality of the market data, transforming it into principal components that capture the most variance. 

📈 Visualizations

Visualize and Compare the Results

Elbow Plot: To determine the optimal number of clusters.
<img width="1402" height="300" alt="Screenshot 2568-10-21 at 12 27 03 AM" src="https://github.com/user-attachments/assets/197065e0-a9c9-466f-9c0c-c7e156d7838f" />

PCA Scatter Plot: To visualize the distribution of cryptocurrencies in the reduced 2D space.
<img width="705" height="303" alt="Screenshot 2568-10-21 at 12 21 51 AM" src="https://github.com/user-attachments/assets/80e73f95-db66-4f8e-b0a3-62eed464fc20" />

Clustered Scatter Plot: To display the cryptocurrencies grouped into clusters.

These visualizations are generated using Matplotlib and Seaborn libraries.
