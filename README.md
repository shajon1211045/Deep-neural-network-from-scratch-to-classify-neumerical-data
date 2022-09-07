# Deep-neural-network-from-scratch-to-classify-neumerical-data
First I created csv files from training and test data and load both data in collaborator for analysis.
Secondly, I loaded the necessary libraries required to build the neural network in python.

After loading the data I labeled first 7500 data as 0(for class 1) and the further 7500 as 1(for class 2) according to the instructions given in the training dataset.
After that I randomized the training dataset and then normalize it for the convenience of training. I split my train data before applying the neural network.

#Creating the neural network class

I create a class DeepNeuralNetwork with two hidden layers having 9 and 19 neurons respectively. I set the number of epochs to 1000 and learning rates to 0.01. I build Relu and Sigmoid function to use as activation function.

#Accuracy after training 

The code generates accuracy and loss after each epoch. The final accuracy and cost (loss) for the training data is 82.78% , 0.38 respectively and  83.29%, 0.37 respectively for validation data.

#Plotting the loss and accuracy 
![loss](Deep-neural-network-from-scratch-to-classify-neumerical-data/accuracy.jpg)
![accuracy](Deep-neural-network-from-scratch-to-classify-neumerical-data/accuracy1.jpg)

I plotted the losses and accuracies to have a better comparison between train and validation data and see if there is any overfitting. 
 
#Validating the network with test data

After applying the trained neural network on the test data the accuracy was 82.9%.
