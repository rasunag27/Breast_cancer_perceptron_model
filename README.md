# Breast cancer prediction using simple MPNeuron and Perceptron model

## Dataset
* The dataset is loaded from sklearn load dataset library which loads the dataset from UCI Breast cancer wisconsin (diagnostic) dataset. The dataset link is https://goo.gl/U2Uwz2.
* The dataset contains two classes (1 and 0), 1 being malignant and 0 being benign. Benign tumors are the one in which the cells are not cancerous and wont spread. On the other hand, malignant tumors are such that the cells are cancerous and can spread to other tissues and organs.
* The dataset has 30 features which is referred as independent variables. The class feature is referred as target/dependent variable.

## MP Neuron model

* The input data takes binary input and results to binary output. The breast cancer input data is not binary and hence it is binarised before feeding it into the model.
* The features are cut into two bins with thresold of 1000. (1 if value>1000, 0 otherwise).
* The MPneuron model consists of a function with single parameter. The MP neuron model is represented as below.

![alt text](https://github.com/rasunag27/Breast_cancer_prediction/blob/main/MPneuron.JPG?raw=true)

## Perceptron model

* The perceptron model is a two-class binary classification machine learning algorithm. 
* It is the simplest type of neural network and consists of single neuron that takes input as features and predicts the output (class label).
* The perceptron model works on the principal of adding weights to each of the features. The perceptron model is represented as below.



