# Crypto-Clustering

Using data from the csv, crypto-market-data, I performed tasks to understand the significance of different datapoints within the dataset. 

1. The data was first prepared by StandardScaler, which normalized the dataset, and coin_id was set as the index
2. Then, I found the Best Value for k Using the original scaled dataframe, using the elbow method.
3. Next, I clustered the cryptocurrency with k-mean through the original scaled data
4. Optimized Clusters through Principal Component Analysis
5. Found the Best Value for k Using the PCA Data
6. Clustered Cryptocurrencies with K-means Using the PCA Data


