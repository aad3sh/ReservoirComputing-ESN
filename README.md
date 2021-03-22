# ESN
I have attempted to model chaotic nonlinear timeseries such as the closing stock prices of S&P 500 companies, using [*reservoir computing*](https://en.wikipedia.org/wiki/Reservoir_computing).
In a way, it shows how much more efficient [echo state networks](http://www.scholarpedia.org/article/Echo_state_network) are compared to lstms or regression when it comes to dynamic systems.
Have compared the efficiency of three different approaches for the same - 
<li> Multiple linear regression
<li> RNN using lstms
<li> ESN based RNNs

###
The code for the ESN model has been obtained from [clemens korndörfer's repo](https://github.com/cknd/pyESN) as it was not available on the keras library. 
I have set the hyperparameters as per optimality and efficiency.
