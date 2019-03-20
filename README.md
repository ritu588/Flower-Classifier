# Flower-Classifier
Flower Classifier built using Transfer Learning in PyTorch

### Overview
This Image classifier is built to distinguish different species of flowers from 102 categories. The dataset can be downloaded from https://s3.amazonaws.com/content.udacity-data.com/nd089/flower_data.tar.gz It uses Transfer Learning technique and was implemented using PyTorch. This project was done using Google Colab.

### Steps
Different pretrained CNN models provided by PyTorch library were tested during the transfer learning process. These are trained on the ImageNet dataset. Models used included
  - VGG19
  - Resnet50
  - Densenet161 
  - Densenet201.

### Results
Densenet201 gave the best validation accuracy of 95.23%.
After that experiments were done with unfreezing some layers of this model, and Densenet201 best validation accuracy improved to 98.53%
