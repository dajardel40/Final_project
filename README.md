# Final_project -  Dog breed classifier
Contents:
1. Project Definition
2. Analysis - model
3. Conclusion

# Project Definition
In this project, CNN (Convolutional Neural Networks) are used in order to create a model that can identify the breed of a dog, when an image is loaded and in the event that it is not a dog, it will say what the breed would be. which resembles the human or the animal.
To achieve the above, 8351 images of dogs are used, which correspond to 133 different breeds. Also 13233 images of humans are used in order to test the model, and also differentiate from each other.
Convolutional Neural Networks are then used, which are more complex neural networks, which are generally used in image classification exercises and artificial vision, among others.
Additionally, Transfer learning is used in the project, which consists of using previously trained networks with many more images, which are adapted and complemented within the current problem, to avoid having to do additional developments, obtaining good results in an optimal time.

## Analysis ##
As explained above, the main information for this project corresponds to the friends corresponding to images of dogs and humans.

Regarding the pictures of dogs, we have 8351 images , which correspond to 133 different breeds. These are divided into 3 groups, training, testing and validation as follows:

There are 6680 training dog images.
There are 835 validation dog images.
There are 836 test dog images.

These images have different sizes, image qualities and are not balanced between different breeds of dogs.

Regarding the images of humans, there are 13233 which also correspond to different people, in different positions and with different backgrounds.

# Model

As explained in the problem statement, in order to be able to identify the breed of a dog in a "simple" way, a CNN can be trained, which, with the help of Transfer learning, allows us to have a model that can classify an image that does not has been previously shown to the model and that it be classified according to definitions of probability among one of the 133 breeds of dogs with which it was trained.

# Conclusion

The accuracy of the final model on the test data set is 78.24%, which is a good result, if we take into account that the model originally trained without using Transfer Learning offered an accuracy of 3.94%. Subsequently making a model with only one fully connected layer achieves an accuracy of around 48%. So the result of the final model is very good.

When performing the tests on new images we see the following:

In the case of dogs, their breed is correctly identified

