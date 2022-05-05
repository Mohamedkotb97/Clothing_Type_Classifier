# Clothing_Type_Classifier
The Training Dataset has 60,000 Images each of 784 pixels each associated with a label from 10 classes.
The data takfe from Kaggle Competition Link:
https://www.kaggle.com/zalando-research/fashionmnist

# Dataset 
Download CSV files from https://pjreddie.com/projects/mnist-in-csv/

# Description of experiment
Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes

# Labels
Each training and test example is assigned to one of the following labels:

0 T-shirt/top
1 Trouser
2 Pullover
3 Dress
4 Coat
5 Sandal
6 Shirt
7 Sneaker
8 Bag
9 Ankle boot

# Methodology 
For this project we will be going to use deep learning concepts like artificial neural networks and convolutional neural networks to build an image classification model which will learn to distinguish 10 different item images into their respective categories.

# Tools & Skills
Python 3.6 - Keras, Tensorflow, Convolutional Neural Networks.

# Run
Uploade the notebook on Colab and run all cells on GPU 

# Result
CNN model 
Loss: 0.1762
Accuracy: 0.9370

# Acknowledgements
Original dataset was downloaded from https://github.com/zalandoresearch/fashion-mnist

Dataset was converted to CSV with this script: https://pjreddie.com/projects/mnist-in-csv/
