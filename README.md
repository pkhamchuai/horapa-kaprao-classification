# Image classification of Horapa and Kaprao images

## Background
In May 2022, a Facebook page [Tautology Thailand](https://web.facebook.com/tautologyai/) shared a [post](https://web.facebook.com/tautologyai/posts/pfbid0vmPVLLuwsZGjNogQrwaWUinSJnhrPK1de6sFfvLJotYzTsMaBuDdXq2jktMbUictl) about a dataset which consists of images of 2 types of plants, Thai basil (Horapa) and Holy basil (Kaprao). These 2 types of plants are pretty hard to distinguish for many people. The dataset was originally prepared and used in a university course.

The goal is to classified the pictures of these 2 types of plants, preferably using an AI. The dataset is available [here](https://github.com/TAUTOLOGY-EDUCATION/DATASET/tree/main/HorapaVsKaprao).

TitorPs360 created a model and shared his codes [here](https://github.com/TitorPs360/horapa-vs-kaprao). I would like to thank him for his codes which makes my life much easier. I used his data processing and result presentation parts in my code.

## Implementation
My (first) model is based on a pre-trained ResNet152 model (I'm just trying to learn about stuffs here). It is implemented using Tensorflow and Keras. So far, the model could correctly classify 103/107 test images, or about 96.26%. A confusion matrix is shown below. Please see the notebook file for more details.

![confusion matrix](https://github.com/pkhamchuai/horapa-kaprao-classification/raw/main/fig/output.png)
