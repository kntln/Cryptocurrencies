# Cryptocurrencies
![Cryptocurrencies](https://www.technewsworld.com/wp-content/uploads/sites/3/2022/02/bitcoin.jpg)

## Overview of the Project
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. Therefore, they have asked to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment. The data that will be used needs to be processed to fit the machine learning models. Since there is no known output, unsupervised learning will be used. For this analysis the following will be applied:
1.  Preprocessing the Data for PCA

- Cleaning data and scaling the data using **`StandardScaler()`**

2.  Reducing Data Dimensions Using PCA
- Principal Component Analysis (PCA) is a statistical technique to speed up machine learning algorithms when the number of input features (or dimensions) is too high. PCA reduces the number of dimensions by transforming a large set of variables into a smaller one that contains most of the information in the original large set.

3.  Clustering Cryptocurrencies Using K-means
- K represents how many clusters there will be. These clusters are then determined by the means of all the points that will belong to the cluster. The K-means algorithm groups the data into K clusters, where belonging to a cluster is based on some similarity or distance measure to a centroid. 
4. Visualizing Cryptocurrencies Results

## Results

### Elbow Curve
- An easy method for determining the best number for K is the elbow curve. For this analysis, the best nunmber of K is 4 as shown in the figure below.

![Elbow Curve](https://github.com/kntln/Cryptocurrencies/blob/main/Figures/Elbow_Curve.png)

### 3-D Scatter Plot
- To visualize the clusters, 3-D scatter plot was used.

![3D Scatter Plot](https://github.com/kntln/Cryptocurrencies/blob/main/Figures/3D_PCA.png)

### Tradable cryptocurrencies

- The total number of tradable cryptocurrencies is 532. 

![Tradable cryptocurrencies](https://github.com/kntln/Cryptocurrencies/blob/main/Figures/Crypto_Table.png)

### TotalCoinsMined vs TotalCoinSupply 2-D Scatter Plot

- An **`hvplot`** scatter plot with TotalCoinsMined on the x-axis while TotalCoinSupply on the y-axis based on class.

![2-D Scatter Plot](https://github.com/kntln/Cryptocurrencies/blob/main/Figures/2D_Scatter_Plot.png)
