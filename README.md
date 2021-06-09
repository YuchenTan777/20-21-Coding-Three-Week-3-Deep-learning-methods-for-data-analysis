# 20/21 Coding Three-Week3 Deep learning methods for data analysis

## At the end of your notebook, type your answers to the following questions
* Were you able to improve accuracy over the initial approach?

 I added epoch to the original method, added a dropout layer and adjusted the dropout parameters, and added a pooling layer as well.
 The accuracy has been significantly improved compared to the original.
 
* If you wanted to achieve better performance on this dataset, and you had a lot more time, what do you think would be good things to try out?
 
According to the data, CNNs converge rapidly in the first 100 training iterations, converge very slowly after 10,000 iterations, stabilize after 15,000 iterations, and maintain the same accuracy rate after 17,500 iterations.

<img src="https://github.com/YuchenTan777/CodingThree-Week3/blob/main/image/v2-4993c801e7184c04bc7e388ebbba8325_1440w.jpg">

**So to improve the accuracy we can increase the number of epochs**

At the same time, the number of layers, structure (convolutional kernel size, depth, step size, number of neurons) and various other **hyperparameters** (dropout, learning rate, batch, epoch) of the CNN network can be adjusted to finally obtain a CNN network with better prediction accuracy.

In addition, we can further **improve the data quality and optimize the data** in addition to improving the algorithms and models. This includes balancing the dataset, generating more data, etc.

## Rreference

https://machinelearningmastery.com/improve-deep-learning-performance/

https://towardsdatascience.com/deep-learning-performance-cheat-sheet-21374b9c4f45


