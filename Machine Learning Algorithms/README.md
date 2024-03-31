# ML-Bootcamp


**Linear Regression**  : For this model I will first split the dependent and independent variables using slicing method of Python.
Then I will make a function to update the weights, and two more functions to differentiate the cost function with respect to w1 and w0.
Then I will make a class of Linear Regression, in this class there will be a constructor, predict function, update function and 
gradient descent function.


**Polynomial Regression** : For this I have do same coding as of Linear Regression, in addition I have to square the dataset and concatenate
it the dataset.


**Logistic Regression** :  For this model I will first split the dependent and independent variables using slicing method of Python.
Then I will make a Sigmoid function so that all values lies between 0 to 1, and a Cost function. Then I will make a class of
Logistic Regression in which there will be a constructor, predict function, update function and gradient descent function.


**KNN(K Nearest Neighbours)** : In this model if I want to classify a datapoint then I have to compare it with it’s neighbouring datapoints.
For this first I will split the dependent and independent variables using slicing method of Python. Then I will make an Euclidean 
function to measure the distance between two datapoints. Then I will make a class which will contain a constructor and a KNN function.
In KNN function I will first measure the euclidean distance between the input and training datapoints and then I will sort it in ascending order.
Then if we iterate it over the first K elements, we will get the index of the most occurring value.


**K-Means Clustering** : For this model first I will make an Euclidean function to measure the distance between two datapoints.
Then I will make a class for KMean which consist of a constructor and a function which will first randomly initialize the clusters centers,
then after evaluation it will give a list of cluster centers closer to each datapoint. 


**Neural Network** : For this model I will first create input layers using slicing method of Python. Then I will make a Sigmoid function,
a derivative function and a class of neural network which will contain a constructor, activation function for the first layer, a backward
propagation function which will calculate gradient of loss function and update function. 
