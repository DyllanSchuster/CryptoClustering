# CryptoClustering

This challenge I analyzed the data of crypto price percentage changes over different seasonalities, such as 24hr, 7days, 30days and etc. This was done to cluster cryptos into groups based on similarities in their price percentage changes over time. More specfically, KMeans was used on the scaled data at first, and then the Principal Component Analysis (PCA) was conducted on the same scaled data. Furthermore, an elbow curve analysis was conducted after each model to determine the best number of clusters to employ. 
