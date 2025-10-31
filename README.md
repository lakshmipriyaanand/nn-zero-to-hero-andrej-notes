# **Summary of NN-zero-to-hero Andrej Karpathy's series**

Neural Networks are mathematical expressions in case of MLP take input as a data, weights ,bias and parameters.

First Forward pass > Finding loss (measures the accuracy of the predictions)> Backward pass > updating the parameter > finding loss (less than the previous one) and check whether the ypred value is close to ys

Loss function would be generally low when our ypred( predicted values) are similar/ close to our desired target values , which means our neural network is good. So we generally focus on reducing the loss function.

Once forward pass has been done and we found the loss function. We do backward pass (backpropagation) to find the gradient and then we know how to tune all our parameters to decrease the loss locally.

We have to iterate this process and each step is called ‘Epoch’ . 1 Epoch - 1 time of ( Forward pass - backward pass - update parameters). We’ll be running these multiple times . This process is called Gradient Descent. 

So we simply follow the gradient information and that minimised the loss and that loss is arranged so the loss is minimised , the network is doing what you want it to do it
