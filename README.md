# Module-19-Challenge_CryptoClustering

Used knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. This was achieved by reading in the crypto_market_data.csv file and performing the following analysis:

* Prepared the data using StandardScaler() from scikit-learn
* Used the elbow method to find the best value for k using the original scaled dataframe
* Clustered the cryptocurrencies for the best value of k=4 on the original scaled data
* Optimzed the clusters using PCA to reduce the features to three principal components
* Used the elbow method to find the best value for k using the PCA data
* Clustered the cryptocurrencies for the best value of k=3 on the PCA data
* Compared the results to determine that the impact of using PCA with fewer features to cluster the data using K-Means was a clear separation of clusters with most of the points contained in one cluster, while the 2 outliers are contained in each of their own clusters.
