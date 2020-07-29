# Overview
- The CIFAR-10 dataset has 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. 
- Used Google Colab, a cloud-based platform, to train Convolutional Neural Network (CNN) models with and without transfer learning. 
- Transfer learning CNN model was trained on top of the VGG16 model of Keras. 
- This project was a 10-class classification problem.

# Methodology
- Polished the dataset by loading the data set from CIFAR-10 and splitting it into train and test data.
- Upsampled the images from 32x32 pixels to 64x64 pixels to improve the performance of the model.
-  CNN model without transfer learning, applied four Convolutional layers with 32, 32, 64 and 64 neurons (kernels) respectively.
- Applied kernel size of 3x3 and had two Max Pooling layers with pool sizes of 2x2 and 1x1 stride to reduce variances and computations for our model. 
- Had a Dense layer with 512 neurons and a Dropout layer with a probability of 50% to drop a neuron.

# Result 
##Wihtout transfer model:

[![Screen-Shot-2020-07-28-at-8-15-42-PM.png](https://i.postimg.cc/9QZ9WNHQ/Screen-Shot-2020-07-28-at-8-15-42-PM.png)](https://postimg.cc/cv1ChhJp)

## With trasnfer model:

[![Screen-Shot-2020-07-28-at-8-15-46-PM.png](https://i.postimg.cc/SK4Mj7m7/Screen-Shot-2020-07-28-at-8-15-46-PM.png)](https://postimg.cc/w1WvGNy7)