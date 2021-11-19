# Signature-Verification

Signature verification are highly viable in order to identify individuals in organizations, finance divisions and in other events. Verifying signatures is an important one in some of the fields because a fraudulent signature would affect the real owner of a particular bond or any agreement signed etc. So, identifying genuine signatures becomes an important part here . Advancement in classification of images using deep learning networks has become an opportunity for solving this problem. This study is the classification of signatures of 10 users, each user having 50 genuine signatures having 400 test image and 100 train images.More over Deep Learning Convolutional Neural Networks (CNN) were used. A Convolutional Neural Network (CNN) is a neural network that has one or more convolutional layers and are used mainly for image processing, classification, segmentation and also for other auto correlated data.

# Experimental Setup

* Data collection,
* Preprocessing,
* Creating model,
* Training the model,
* Result and comparitive study

# Data Collection

In this process, the dataset(Figure 1.1) consists of signature images of about 100 test
and 400 train images. These images are taken in the resolution of 128x128. All these signature
images are taken from 10 users and arranged with 10 classes as each class for a user with 50
signature images. 

![image](https://user-images.githubusercontent.com/81804003/142645732-dfc20c82-83de-4c76-b8ce-08e7a53981f3.png)
*Figure 1.1 - unprocessed image*

# Preprocessing

Data preprocessing is a process of preparing the raw data and making it suitable for a machine learning model. here we have created our dataset and done some **feature** **extraction**(As in Figure 1.2) using openCV to reduce the noisiness in data and make the data cleaner for further processing. 

![image](https://user-images.githubusercontent.com/81804003/142647259-f8a67877-d132-415e-b62a-5398bd287431.png)

*Figure 1.2 - feature extraction*

In this step first we have took an unprocessed image and sharped it, then converted it into binary image, then we have Masked the image and have done invert masking. Afetr applying those filters our dataset looks like this (as in Figure 1.3).

![image](https://user-images.githubusercontent.com/81804003/142649202-a0848d09-7f42-467a-b368-41915e569dcf.png)
*Figure 1.3 - dataset*

# Creating Model

There are four types of models used :

1. CNN with 4 convolution layers
2. CNN with 3 convolution layers
3. VGG16
4. InceptionV3 

# Training the model

The Model was trained with different Epochs and by adjusting the Hyperparameter Tuning with Batch size, steps per epochs and with different learning rates.

# Result and Comparitive study

After training Different Models with different paramters the best we have gotten the validation accuracy so far is **95%** in our CNN model with 3 convolutional layers. and **94%** in CNN model with 4 convolutional layers and in VGG 16. and **95%** in Inception V3. 





