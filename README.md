# TextClassification

A Feedforward neural network for text classification consisting of:

– One-hot input layer mapping words into an Embedding weight matrix 

– One hidden layer computing the mean embedding vector of all words in input followed by a ReLU activation function

– Output layer with a softmax activation 

– Stochastic Gradient Descent (SGD) algorithm with back-propagation to learn the weights of the Neural network





# Results:


![image](https://user-images.githubusercontent.com/17896055/135775575-fc55f33f-2ed7-4be2-a2e7-7136497356f3.png)


Average Embedding (Pre-trained) model is better than the other two as primarily because of the better performance which is evident from the metrics. One reason that this model performs better is the use of pretrained vectors as compared to the random embedding weights used for the Average Emdedding model for which the weights were randomly assigned. As for the Average Embedding (Pre-trained) + X hidden layers model, adding another hidden layer may have added uncessary complexity in the architecture which did not contribute as aexpected but it still performs better than the Average Embedding model.
