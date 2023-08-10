# Viral Pneumonia, Covid Detection using ANN 
## ANN
The Covid-19 pandemic happened 3 years ago and it has left quite an impact in all aspects around the world. However, it probably left quite a lot of data about that disease such as: Lungs, brain, .. In this project I will train my model to recognize which lungs are infected with covid , inflammation. healthy lungs or lungs. My dataset has been uploaded with the file ipynb. In this project, I will use Pytorch. If you use Google Colab then you don't need to install just import torch normally. On the other hand, when you use another environments need to install Pytorch using command line in terminal.

- For this project, I will use ANN to train this dataset. (I know it won't be as good as CNN (feature extraction)
- The structure of an ANN includes: An input layer, one or more hidden layers and an output layer.
- Use fully connected layers (or dense layers), where every unit in each layer connects to all units in the previous and subsequent layers.
- Here is a description of the ANN:

  

![Multi-Layered-Artificial-Neural-Network-7](https://github.com/Quang1129/Covid19-Xray-Detection/assets/72682141/f3664e18-0353-4685-88c9-cc3f8ffe14a0)


+ Input Layer:

Get external input (e.g. images, text, numeric data).
Pass data to neurons in the first hidden layer.
+ Hidden Layers:

Each neuron in the hidden layer computes a linear combination of the inputs from the neurons in the previous layer, and then applies a nonlinear activation function to compute the output value.
This operation is usually performed through multiple hidden layers (if any) to learn more complex patterns in the input data.
Each hidden layer can contain different numbers of neurons and use different activation functions.
+ Output Layer:

The last layer of the network, receiving the output values from the last hidden layer.
Perform the same computation as hidden neurons, including linear combination and activation function.
The output of this layer is often related to the goal of the model, such as classification of classes, prediction of values, or any other task the network is trained to perform.

+ Training and Optimization:

The ANN needs to be trained by adjusting the weights and biases of the neurons.
Training often uses optimization algorithms such as gradient descent to adjust the weights so that the network's prediction error decreases over time.
The training data is used to compare the predicted output with the actual value and calculate the gradient to adjust the weights.

+ Backpropagation:

The backpropagation process backpropagates the errors from the output layer back to the hidden layers, thereby calculating the gradient and adjusting the weights.
This helps to update the weights to minimize the error between the prediction and the actual value.
Prediction and Testing:

After the network has been trained, it can be used to predict outcomes for new data.
New data is transmitted over the network and the output is calculated from the output layer.
 
