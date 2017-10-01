# DLND-P2 Image Classification
In this project, I try to classify images from the CIFAR-10 dataset. The dataset consists of airplanes, dogs, cats, and other objects. I first preprocess the images, then train a convolutional neural network on all the samples. 

The sample image is 32*32*3 just like the following: 

<img width="253" alt="download" src="https://user-images.githubusercontent.com/24641283/31058462-f99314e4-a6c1-11e7-8553-df038928a931.png">

In the neural network I use, there are two layers of convolutional layers and two fully-connected layers and dropout is applied to the last layer. We get a validation accuracy of ~63% using this simple CNN. 
