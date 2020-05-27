# Facial Keypoint Detection

This project will be all about defining and training a convolutional neural network to perform facial keypoint detection, and using computer vision techniques to transform images of faces. 

## Libraries
* Numpy
* OpenCV
* Matplotlib
* Pytorch

## File explanation

The explanations of the project's files are:

* 1.Load and Visualize Data.ipynb: Explore the training and test set to get a general view of the dataset: its size, file type, visualize an example image. This notebook forms our decision on how to preprocess the images.

* 2.Define the Network Architecture.ipynb: Build a Neural Network model in model.py file, and train the model using the preprocessed dataset.

* 3.Facial Keypoint Detection, Complete Pipeline.ipynb: Use an open-CV pretrained Haar Cascade model for face detection, then draw keypoints on the face/faces using the Neural Network model that we train in the second notebook (2. Define the Network Architecture.ipynb).

* model.py: Contains the Neural Network model for the keypoint detector trained in the second notebook (2. Define the Network Architecture.ipynb).

* fkd_report.pdf: Explain the project dataset, methodology, pipeline, and results.

## References

The projects are built upon this repository files: https://github.com/udacity/P1_Facial_Keypoints
