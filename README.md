# devAkademiSahibinden

This software consists of two main parts.
1) Python GUI program
2) web API 

These two programs has almost the same functionalities. It can be said that API is the extension of GUI part to the web users so that anyone can get the data they need. Hence, that might cause an increase in the transaction volume of SCoin.

There are 3 main functions that program can provide. 

1)Investment Analysis: The SCoin change over time has been seen. Because of the underlying exponential pattern, it is critical to know whether one should invest.  The historical data is provided by Sahibinden so that it is used to predict the alternative current value. Then this predicted value is compared by the realtime value of SCoin. As result of that comparison, the program produces an index. Then, based on the result of the index, investment status can be learned.

2) Coin Value: Since it is crucial to know the current value of SCoin, the program can present those by exploiting the web API's.

3) Coin Value Estimation: In this part. User can learn the estimated value of SCoin.

Note: Same functionality holds for Bitcoin as well. Data is pulled from another web API. The reason that the program has BTC is a comparison between investment score of SCoin and BTC could be done. So that the users might buy or sell their coins based on the current situation. 

Note2: If the data is provided with more features than only time. There could be a better prediction algorithm instead of linear one.

Note3: Web API of the program can lead to inflation in database. Because in every query a new node is being created.

Note4: The code is bit messy. Because I used the notebook as sketchbook in a sense and could not had time to clean it. Sorry for that ^^
