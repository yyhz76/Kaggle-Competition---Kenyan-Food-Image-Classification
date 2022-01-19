# Kaggle-Competition---Kenyan-Food-Image-Classification

This competition is about classification of Kenyan food images. The dataset consists of 8,174 images in 13 Kenyan food type classes.

![alt text](https://github.com/monajalal/Kenyan-Food/blob/master/img/KenyanFood13.png?raw=true)



The details of the competition: https://www.kaggle.com/c/opencv-pytorch-dl-course-classification


# Summary
Trained 50 epochs using modified ResNet152 network

Modified the original ResNet152 single fully connected layer to 2 fully connected layers with 2 dropout layers

Unfreezed Layer 4 in the original ResNet152 network and the 2 newly added fully connected layers. Freezed all other layers (Transfer Learning)

Used the model weights at Epoch 31 (Early Stopping)

Training Accuracy: 81.9%

Validation Accuracy: 78.3%

Test Accuracy: 77.5%

# TensorBoard Dev Scalars Log Link
https://tensorboard.dev/experiment/0NHYnHGqS2OuOouVrxKejw/
