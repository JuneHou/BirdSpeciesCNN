# BirdSpeciesCNN
This is the project of IE7275 Data Mining course, which taught by professor Dr.Arasu at Northeastern University in 2022 Spring.

## Problem Statement
This project is inspired by the dataset from Kaggle: https://www.kaggle.com/datasets/gpiosenka/100-bird-species. To monitor the biodiversity and to protect endangered bird species, ecologists have to carry out time-consuming observations. However, this problem can be solved by machine learning, with lower costs in both professions and time.

## Data Description
The dataset of 350 bird species comes from Kaggle and is continuously updated. Currently, it consists of 50944 training images, 1750 test images (5 images per species), and 1750 validation images (5 images per species). All images are 224 X 224 X 3 color images in jpg format. Data set includes a train set, test set, and validation set. Each set contains 350 subdirectories, one for each bird species.

## Mythology
- Neural Network as a biologically inspired simulation has outstanding performance on clustering, classification, and pattern recognition. 
- CNN is the domain neural network for deep learning of image and video. The filter of CNN can play the role of feature extraction, and the channel of each layer can help retain the spatial features.
- Pre-trained VGG and ResNet model are applied in the model experiment. The result shows VGG isn't fit this dataset, so it is replaced by the self-build model in the model implementation step. 

# Reference

Rachit Tayal. (2020). Deep Learning for Computer Vision. 
	https://towardsdatascience.com/deep-learning-for-computer-vision-c4e5f191c522
Poonamvligade. (2020). Building ResNet34 in PyTorch.
  https://github.com/jarvislabsai/blog/blob/master/build_resnet34_pytorch/Building%20Resnet%20in%20PyTorch.ipynb
Purva91. (2020). Top 4 Pre-Trained Models for Image Classification with Python Code.
  https://www.analyticsvidhya.com/blog/2020/08/top-4-pre-trained-models-for-image-classification-with-python-code
