# CryptoClustering

Use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Steps:
1. Prepare the data using `StandardScaler()` from `scikit_learn` to normalize the data from the CSV file.
2. Find the best value of k using the scaled data and the elbow mehtod.
3. Cluster crytocurrencies with k-means using the scaled data.
4. Plot clusters using hvplot.
5. Perform PCA on the scaled data to reduce features to three principal components.
6. Retrieve the explained variance.
7. Find the best value of k using the PCA data and the elbow method.
8. Cluster cryptocurrencies with k-means using the PCA data.
9. Plot PCA clusters using hvplot.
