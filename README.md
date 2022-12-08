# Car-Brand-Detection
Here I'm implementing the car brand classification using images of the car of 3 brands which are Mercedes, Audi, and Lamborghini.
This data set includes the car images used for classification of the car brand. Here, I have two folders namely train and test, each of them has three folders named Lamborghini, Audi, and Mercedes which has random images of the car.

I have used transfer learning here because it is very useful since most real-world problems typically do not have millions of labeled data points to train such complex models.

I'm using Keras library because it enables fast experimentation with deep neural networks.
I built the model with the help of Resnet 50 as it can train deep neural networks with many layers. I'm also using imagenet weights so that i dont have to train my neural network from the scratch. 
For creating new training samples from the one that available im using Image Augmentation performed it by using Image Data Generator.

Resnet 50 architecture:
![0_tH9evuOFqk8F41FG](https://user-images.githubusercontent.com/83118429/206462019-2ed4351b-ce55-421c-87ff-540585a34529.png)
