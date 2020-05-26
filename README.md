# Facial Keypoint Detection

This project will be all about defining and training a convolutional neural network to perform facial keypoint detection, and using computer vision techniques to transform images of faces. 

## Libraries
* Numpy
* OpenCV
* Matplotlib
* Pandas

## Workflow

The workflow of the project is explained by the notebook(.ipynb) files:

* 1. Load and Visualize Data.ipynb: Explore the training and test set to get a general view of the dataset: its size, file type, visualize an example image. This notebook forms our decision on how to preprocess the images.

* 2. Define the Network Architecture.ipynb: Build a Neural Network model in model.py file, and train the model using the preprocessed dataset.

* 3. Facial Keypoint Detection, Complete Pipeline.ipynb: Use an open-CV pretrained Haar Cascade model for face detection, then draw keypoints on the face/faces using the Neural Network model that we train in the second notebook (2. Define the Network Architecture.ipynb).

Furthermore, the complete pipeline of the Facial Keypoints Detector can be viewed by the image below:


## References

The projects are built upon this repository files: https://github.com/udacity/P1_Facial_Keypoints
