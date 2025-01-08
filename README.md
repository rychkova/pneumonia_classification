# Pneumonia classification

This repo contains image classification project using Convolution Neuron Network.   

It is based on the RSNA Pneumonia Detection Challenge on kaggle: https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/overview.  

The model is trained on the X-ray images with and without signs of pneumonia. It uses ResNet-50 architecture, which is a powerful deep convolutional neural network that has proven highly effective for image classification tasks.

Project is adopted from the "Deep Learning with PyTorch for Medical Image Analysis" course on Udemy.

To run the notebooks, first install envirnment using provided yml file:
```
conda env create -f CNN_env.yml
```

After that activate the environment and run jupyter:
```
conda activate CNN_env
jupyter lab
```