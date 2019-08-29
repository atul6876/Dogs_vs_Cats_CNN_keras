# Dogs_vs_Cats_CNN_keras
Classic binary image classification using Convolutional Neural Network Model built using Keras with TensorFlow backend.

This repository contains the code to predict whether the picture contains the image of a dog or a cat using a CNN model trained on the images from the kaggle dataset (not all the images, but I use image augmentation techniques that ensure that the model sees a new "image" at each training epoch. I also use pretrained models with deeper architectures for image classification. I have used Keras's blog on building and compiling a CNN model as a template for most of my code and directory structure.

I have also used the widely used VGG16 model and modified the model's output layer for binary classification of dogs and cats. I am using the pre-trained weights, and only training the final layer weights at each training epoch. As you'll see, even with very limited training epochs, the VGG model outperforms the simple ConvNet model by 15% (88% accuracy as compared to 73% of the ConvNet).

