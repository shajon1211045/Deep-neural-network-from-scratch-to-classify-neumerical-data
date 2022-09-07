<h1> Deep-neural-network-from-scratch-to-classify-neumerical-data</h1>
First I created csv files from training and test data and load both data in collaborator for analysis.
Secondly, I loaded the necessary libraries required to build the neural network in python.

After loading the data I labeled first 7500 data as 0(for class 1) and the further 7500 as 1(for class 2) according to the instructions given in the training dataset.
After that I randomized the training dataset and then normalize it for the convenience of training. I split my train data before applying the neural network.

#Creating the neural network class

I create a class DeepNeuralNetwork with two hidden layers having 9 and 19 neurons respectively. I set the number of epochs to 1000 and learning rates to 0.01. I build Relu and Sigmoid function to use as activation function.

#Accuracy after training 

The code generates accuracy and loss after each epoch. The final accuracy and cost (loss) for the training data is 82.78% , 0.38 respectively and  83.29%, 0.37 respectively for validation data.

#plotting the data 

![accuracy](https://user-images.githubusercontent.com/59179489/188814806-b43eb5b5-202d-41d3-b410-058f00e9b1ce.jpg)

![accuracy1](https://user-images.githubusercontent.com/59179489/188815056-a7a1e142-96dd-471f-b6e2-afe4fa942ae1.jpg)

The loss and accuracy graph of train and validation are simillar. So, there was no overfitting.
 
#Validating the network with test data

After applying the trained neural network on the test data the accuracy was 82.9%.
