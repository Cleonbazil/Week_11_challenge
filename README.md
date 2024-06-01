# Week_11_challenge

**In this project we examine how well the KMeans algorithim from Sklearn clusters data. After importing the necessary dependencies we perform a succint exploratory analysis:**


#### Data frame
**'+-----------------+-------------------------------+------------------------------+-------------------------------+-
Coin Id            Delta%_24h    Delta%_7d    Delta%_7d    Delta%_14d    Delta%_30d    Delta%_60d    Delta%_200d



#### Features statistical metrics




**Above the mean, standard deviation, count and other metrics for the data are displayed to obtain a sense of the feature range and behavior
afterwards the data is scaled to prevent the results to be skewed by one feature.


#### Scaled data




**To continue our analysis process we define a function dubbed best_k which takes in the scaled dataframe and returns another 
with the inertia values for each number of clusters examnied.


#### Inertia values data frame



#### Elbow curve visualization

![Alt text](Resources/elbow.png)
