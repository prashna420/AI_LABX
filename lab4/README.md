<h1 align="center"> Comparative Analysis of Deep Learning Architectures on CIFAR-10</h1>
<p align="center">
 <img src="https://img.shields.io/badge/Python-3.14.2-000000"/>
  <img src="https://img.shields.io/badge/Framework-PyTorch-1A1A1A"/>
  <img src="https://img.shields.io/badge/Dataset-CIFAR--10-2D2D2D"/>
  <img src="https://img.shields.io/badge/Models-NN%20vs%20AlexNet%20vs%20TinyVGG-333333"/>
</p>

# **TITLE: Comparison between three different deep learning architectures (NN, AlexNet, and TinyVGG) on the CIFAR-10 dataset**

## **INTRODUCTION:**

In this project, 3 deep learning architectures are implemented on the CIFAR-10 dataset and then their results are evaluated accordingly.
Their impact on the performance on the image classification with respect to their architecture will be studied.

## **DATASET(CIFAR-10)**

### Statisics:


|Total Images:    60,000
|Training Images: 50,000
|Test images:     10,000
|Image Size:      32x32 pixels
|Color CHnells:   3(RGB)
|Number of classes:10
|Images per class: 6000


### Class   labels:
|Airplane    0
|Automobile  1
|Bird        2
|Cat         3
|Deer        4
|Dawg        5
|Frog        6
|Horse       7
|Ship        8
|Truck       9


## **BACKGROUND(Architecture)**

### Neural Network:

This is the baseline model for comparison as it does not concern itself with the spatial structure of the images. The CIFAR-10 images(32x32x3) is flattened into a 1-D vector with 3072 features.

Hence, the input layer ends up with 3072 neurons.

The output layer has 10 neurons(one for each class).

### ALEXNET:

Alexnet is a CNN developed for image classification tasks which pioneered as the first widely recognized application of deep convolutional networks in large-scale visual recognition.
It has large 11x11 kernels.
Since the original AlexNet was designed for 224x224 images, modifications have been made to suppolrt 32x32 images.

### TinyVGG:

TinyVGG is a simple CNN architecture designed with efficiency in mind.
It has smaller 3x3 kernels. It works best for smaller scale inputs like CIFAR-10.
It provides a good balance between complexity and performance.


# **EXPECTATIONS**

In this comparison, AlexNet is expected to outperform the other two models. TinyVGG is expected to give output close to AlexNet. The NN is expected to be relatively worse due to it ignoring spatial information. AlexNet and TinyVGG preserve spatial hierarchies and can detect pattern in images. 

# **RESULTS**

PENDING...


# **DISCUSSION AND CONCLUSION**

PENDING...
