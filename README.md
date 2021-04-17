# Covid19 Detection with Chest X-Ray in Pytorch

Network: ResNet18


# Implementation of COVID19 detection using Pytorch

The network architecture is ResNet18.

---

## Overview

### Data

Dataset from [COVID-19 Radiography Dataset](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) on Kaggle

### Training

The model is trained for 1 epoch.

After even 1 epochs, calculated accuracy is about 0.989.

Loss function for the training is basically just a binary crossentropy.

The optimizer is Adam.

---

## How to use

### Dependencies

This tutorial depends on the following libraries:

* Pytorch


### Follow the notebook to run the code


### Results

Use the trained model to do classification on test images.

![fig/predictions.png](fig/predictions.png)
