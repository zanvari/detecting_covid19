# Detecting COVID-19 with Chest X Ray using PyTorch¶


The network architecture is ResNet18.


### Dataset

Dataset from [COVID-19 Radiography Dataset](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database) on Kaggle

### Training

The model is trained for 1 epoch. After even 1 epochs, calculated accuracy is about **0.989**.

Loss function for the training is basically just a binary crossentropy. The optimizer is Adam.

---

## How to use

### Dependencies

This tutorial depends on the following libraries:

*  Pytorch
*  torchvision
*  numpy
*  PIL
*  matplotlib

Follow the notebook to run the code.

### Results

Use the trained model to do classification on test images.

![alt text](https://github.com/zanvari/detecting_covid19/blob/main/figs/result.png)
