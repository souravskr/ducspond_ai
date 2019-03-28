# **Neural Networking with Street View House Numbers (SVHN) Dataset**

[SVHN](http://ufldl.stanford.edu/housenumbers/) is a popular real-world image dataset which shares some similarities with [MNIST](http://yann.lecun.com/exdb/mnist/) dataset. It requires minimal data pre-processing and formatting. In this dataset, all the images are **RGB** and in fixed shape of **32-by-32 pixels**. The dataset consists of **73,257 and 26,032 digits with total 10 classes** for training and testing respectively. 


## Files:

* **SVHN_CNN_64*2.ipynb** : with convolution neural network
* **epoch_acc_loss.jpg** : in-sample accuracy and in-sample loss
* **epoch_val_acc_loss.jpg** : out of sample accuracy and out of sample loss
* **SVHN_CNN_64*2.h5** : we saved our model


## Findings:

We have evaluated our model with testing data and plotted several images with their predictions with percentage (out of 100) as follows:
![Our predictions](https://github.com/souravskr/ducspond_ai/blob/SVHN_CNN/predictions.png)

We also have plotted some graphs of in-sample and out of sample accuracy with loss based on the epoch value as follows:
![loss_accuracy](https://github.com/souravskr/ducspond_ai/blob/SVHN_CNN/los_acc.jpg)

