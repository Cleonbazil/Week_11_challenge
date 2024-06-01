# Week_11_challenge

**In this project we examine how well the KMeans algorithim from Sklearn clusters data. After importing the necessary dependencies we perform a succint exploratory analysis:**


#### Data frame
**'+-----------------+-------------------------------+------------------------------+-------------------------------+-
Coin Id            Delta%_24h    Delta%_7d    Delta%_7d    Delta%_14d    Delta%_30d    Delta%_60d    Delta%_200d
---------------  ------------  -----------  -----------  ------------  ------------  ------------  -------------
bitcoin               1.08388      7.60278      6.57509       7.67258      -3.25185      83.5184        37.5176
ethereum              0.22392     10.3813       4.80849       0.13169     -12.8889      186.774        101.96
tether               -0.21173      0.04935      0.0064       -0.04237       0.28037      -0.00542        0.01954
ripple               -0.37819     -0.60926      2.24984       0.23455     -17.5525       39.5389       -16.6019
bitcoin-cash          2.90585     17.0972      14.7533       15.749       -13.7179       21.6604        14.4938
binancecoin           2.10423     12.8551       6.80688       0.05865      36.3349      155.619         69.692
chainlink            -0.23935     20.6946       9.30098     -11.2175      -43.6952      403.229        325.132
cardano               0.00322     13.993        5.55476      10.1055      -22.8478      264.514        156.098
litecoin             -0.06341      6.60221      7.28931       1.21662     -17.2396       27.4992       -12.6641
bitcoin-cash-sv       0.9253       3.29641     -1.86656       2.88926     -24.8743        7.42562       93.7308'**


#### Features statistical metrics




**Above the mean, standard deviation, count and other metrics for the data are displayed to obtain a sense of the feature range and behavior
afterwards the data is scaled to prevent the results to be skewed by one feature.


#### Scaled data




**To continue our analysis process we define a function dubbed best_k which takes in the scaled dataframe and returns another 
with the inertia values for each number of clusters examnied.


#### Inertia values data frame



#### Elbow curve visualization

![Alt text](Resources/elbow.png)
