Accuracy on XOR dataset:
1. MLP : 99.5%
2. MLP with L1 regularisation : 89.5%
3. MLP with L2 regularisation : 91%
4. Logistic regression : 100%

MLP and logistic regression learn the exact pattern of the XOR dataset

MLP with L1 and L2 regularisation adds penalty to parameters to prevent overfitting and help the model generalise well. MLP with L1 and L2 regularisation are generalising well. The penalty coefficient is selected using validation data. For L1 regularisation, penalty is 0.001 and for L2 regularisation, penalty is 0.001.

MLP with L1 regularisation makes some parameters zero while L2 regularisation is moving some of the parameters close to zero.