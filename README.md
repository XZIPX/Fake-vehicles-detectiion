# Fake-vehicles-detectiion
This is the repository for the "Fake Vehicles Detection" project, developed for DataSaur 2023. The primary objective of this project is to train a model to identify fake photos of vehicles. This is crucial as people often attempt to evade technical inspections by creating forged images, using tools such as Photoshop and other editing software. In the context of this problem, we perform binary classification, where "0" represents genuine vehicle photos, and "1" represents fake photos, which can be sourced from computer screens, manipulated using Photoshop, or other similar methods.

To achieve this goal, a prebuilt ResNet-50 model implemented in PyTorch was utilized. ResNet-50 is a popular choice for image classification tasks due to its deep architecture and excellent performance.
![0_tH9evuOFqk8F41FG](https://github.com/XZIPX/Fake-vehicles-detectiion/assets/96609166/02b5a765-b32d-4681-b194-cd2af3988082)



## Dataset
The dataset used for training and testing the fake vehicle detection model is not included in this repository. To replicate this project, you will need to acquire a suitable dataset containing genuine and fake vehicle images. This dataset should be organized into two classes - "0" for genuine images and "1" for fake images. It is essential to maintain a proper data split for training and evaluation.

## Model Architecture
The model architecture used for this project is ResNet-50. ResNet-50 is a deep convolutional neural network (CNN) that has demonstrated state-of-the-art performance on various image classification tasks. You can find the pre-trained ResNet-50 model in the PyTorch model zoo.
