This Assignment has 4 problems/tasks for a deep learning model.

1. Vary the number of hidden layers to see the affects on validation and test accuracy.

Observation : The accuracy of the network impacted by the number of hidden layers are reduced  on the accuracy of the network as with the complex problem 
having less number of hidden layers it might be possible that network will not be trained properly. 
The number of hidden layers cross the optimal number of hidden layers (three layers), time complexity increases in orders of magnitude as compared 
to the accuracy gain. The techniques implementing less than three number of hidden layers mostly had a loss in accuracy while the architecture implementing more than 
three numbers of hidden layers were found not to be optimal in terms of time complexity.

2.Vary the number of hidden units or nodes

Observation : If we use a few hidden units we will end up getting high training error and high generalization error due to underfitting and 
high statistical bias. If we use too many hidden units, we may get low training error but still have high generalization error due to overfitting 
and high variance.

3. Using the MSE loss function instead of binary_crossentropy.

Observation - The cross entropy is the best to use in the output layer of your network if it has a sigmoid or softmax nonlinearity. 
If instead we assume the target is continuous and normally distributed, and we need to maximize the likelihood of the output of the net under 
these assumptions,we can use MSE For classification, cross-entropy tends to be more suitable than MSE.

4. Using the tanh activation (an activation that was popular in the early days of neural 
networks) instead of relu

Observation: Increase the loss and decrease in accuracy, we have seen some issues. tanh returned units given more confidence. This is due to "relu" 
as an anctivation funtion that zeros-out negative values. If we not use "relu" the negative values impact the model.

5. Improve the Validation

Observation: By using regularization, 4 epochs are optimal because the model less accuarate but reduced loss.
