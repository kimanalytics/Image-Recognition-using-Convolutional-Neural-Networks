# Image Recognition using Convolutional Neural Networks

Convolutional Neural Network is going to learn differences between a cat and a dog and make predictions.

### Introduction

Problem: Here, our problem is quite simple. Is the image a dog or a cat? However, our neural network isn't. It utilizes convolution methods to be able to predict specific features of an image according to what it learns on a training set. For example, we might say that we can tell the difference by looking for whiskers on a cat or long snout on a dog. But a convolutional neural network looks for many other features based on what we give it in a training set.

Dataset: We have 4000 images of dogs and 4000 images of cats for the training set. For the test set, we have 1000 images of dogs and 1000 images of cats.

Solution: Utilize Convolutional Neural Networks to develop a image feature dectector which will predict if an image contains a dog or a cat.

### Structure

* Data Visualization
* Building the Convolutional Neural Network
* Fitting the Convolutional Neural Network to the Images
* Making New Predictions

### Conclusion

We got a final result of 99.67% accuracy for our training set and 81.88% for our test set. For our 6 sample tests, our model got 5/6 correct. (The last 2 photos were difficult becuase the pets were wearing costumes)

Further improvements to this model could be increasing the epochs to 25 for more deep learning. Also, increasing the image resizing from 64x64 to 256x256 should lead to better results due to higher resolution. Finally, increasing the batch size from 32 to 64 could also lead to better results.
