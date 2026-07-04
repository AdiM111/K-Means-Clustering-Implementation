# K-Means-Clustering-Implementation
Implemented K-Means Clustering with Elbow Method, KneeLocator, and Silhouette Score

# K-Means Clustering

## Project Overview
This project demonstrates the implementation of the K-Means Clustering algorithm using Python and Scikit-learn. It includes data generation, clustering, validation of the optimal K value using the Elbow Method, KneeLocator, and Silhouette Score, along with visualization of the results.

## Features
- Generate synthetic data using `make_blobs`
- Apply K-Means Clustering
- Find the optimal K using the Elbow Method
- Automatically detect the elbow point using KneeLocator
- Evaluate clustering quality using Silhouette Score
- Visualize clusters and centroids

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Kneed

## Project Workflow
1. Import libraries
2. Generate dataset using `make_blobs`
3. Visualize the dataset
4. Apply K-Means
5. Find the optimal K using the Elbow Method
6. Detect the elbow using KneeLocator
7. Calculate the Silhouette Score
8. Visualize the final clusters

## Results
- Optimal K selected using the Elbow Method
- KneeLocator confirms the elbow point
- Silhouette Score evaluates clustering quality
- Final clustered visualization with centroids

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open `K_Means_Clustering.ipynb` and run all cells.

## Author
Aditya Maurya
