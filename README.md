# Potato-Plant-Disease-Classification-using-Deep-Learning-
Developed a deep learning model classifying potato plant images as healthy or diseased with 95% training and 90% validation accuracy. Deployed as a web service for user-uploaded images, aiding in swift plant health assessment.

Project Title: Potato Plant Health Classification using Deep Learning

# Overview:
This project focuses on leveraging deep learning techniques to classify images of potato plants into two categories: healthy and diseased. The aim is to provide a tool that aids in the rapid identification of plant health issues, potentially benefiting farmers and researchers in monitoring and addressing crop diseases.

# Dataset and Model Architecture:
The model was trained on a dataset comprising images of potato plants sourced from diverse online repositories. The architecture of the deep learning model used for classification is as follows:

Input Layer: Image dimensions set to 256x256 pixels with RGB channels.
Preprocessing: Rescaling the pixel values to a range of 0 to 1 and applying random zoom and rotation for augmentation.
Convolutional Layers: Two sets of convolutional layers with increasing filter sizes (32 and 64) followed by ReLU activation functions and max-pooling layers (2x2).
Flattening and Dense Layers: Flattening the output and passing it through dense layers with 256 neurons using ReLU activation, incorporating a dropout rate of 0.5 for regularization.
Output Layer: A single neuron with a sigmoid activation function for binary classification (healthy/diseased).

# Training and Validation:
The model underwent training for 20 epochs using the Adam optimizer and binary cross-entropy loss function. During training, the model achieved the following performance metrics:

# Epoch 1-20: 
The model showcased varying levels of accuracy and loss on the training and validation sets, with the accuracy peaking at around 97% and 95% respectively on the training set and 95% and 93% on the validation set.
Model Deployment:
Upon successful training, the model was deployed as a web service, allowing users to upload images of potato plants for instant classification into healthy or diseased categories.

# Considerations and Next Steps:
While the model demonstrates promising accuracy rates, further evaluation with an unseen test dataset or real-world images would enhance confidence in its generalizability. Continual refinement and potentially incorporating newer data could improve its performance over time.
This project contributes to the field of agriculture by providing a technological solution for early detection and monitoring of potato plant health issues, facilitating timely interventions and crop management strategies.

