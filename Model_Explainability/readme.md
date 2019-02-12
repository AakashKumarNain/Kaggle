# 10 Monkey Species classification

The aim of this notebook is to provide an overview of how to see what is actually happening inside a convolution
neural network. It shows a way to interpret the predictions of a CNN. The two ways that are explored here for 
model explainability are:

* **Visualization of intermediate layers activation maps**
* **[Class Activation Mapping(CAM)](http://cnnlocalization.csail.mit.edu/)**

## Dataset
The dataset can be downloaded from [Kaggle](https://www.kaggle.com/slothkong/10-monkey-species/home)

## Requirements
In order to run the notebook locally, you must have the following packages installed:
* Python>=3.6
* numpy>=1.15
* scikit-learn
* matplotlib
* Tensorflow>=1.12
* Keras>=2.xx
* mlextend
* imgaug
* opencv>=3.4.x


If you don't want to use a local setup and you directly want to view the notebook with proper outputs, 
please visit [nbviewer](https://nbviewer.jupyter.org) and paste the link to this notebook there.
