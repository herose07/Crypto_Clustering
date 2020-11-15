![image](https://user-images.githubusercontent.com/65314799/99164794-02ac6080-26cb-11eb-8e0e-598b3be556fd.png)



# Cryptocurrency Clustering

## Background Information

A prominent investment bank is interested in offering a new cryptocurrencies investment portfolio for its customers, however, they are lost in the immense universe of cryptocurrencies. They ask you to help them make sense of it all by generating a report of what cryptocurrencies are available on the trading market and how they can be grouped using classification.

This assignment accomplishes the following main tasks:

**Data Preprocessing:** 
    - Prepare data for dimension reduction with PCA and clustering using K-Means.
**Reducing Data Dimensions Using PCA:** 
    - Completion of this task results in the following dataframe:
    
![image](https://user-images.githubusercontent.com/65314799/99163025-bf052700-26c9-11eb-95ab-be912f9c867b.png)

**Clustering Cryptocurrencies Using K-Means:** 
    - Create an Elbow Curve to find the best value for k.
    - Once the best value for k is defined, the Kmeans algorithm is used to predict the k clusters for the cryptocurrencies data. 
    - Completion of this task results in the following dataframe:

![image](https://user-images.githubusercontent.com/65314799/99163035-da703200-26c9-11eb-80b1-2e527dd5149a.png)

**Visualizing Results:** 
    - Create a 3D-Scatter using Plotly Express to plot the clusters.
    - Use `hvplot.table` to create a data table with all the current tradable cryptocurrencies.
    - Create a scatter plot using `hvplot.scatter`, to present the clustered data about cryptocurrencies having `x="TotalCoinsMined"` and `y="TotalCoinSupply"` to contrast the number of available coins versus the total number of mined coins.
