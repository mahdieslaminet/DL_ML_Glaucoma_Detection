# DL_ML_Glaucoma_Detection

# Comprehensive Review of Machine Learning and Deep Learning Techniques for Glaucoma Detection

This repository contains the source code, data, and results for the study titled "Comprehensive Review of Machine Learning and Deep Learning Techniques for Glaucoma Detection."

## Introduction
Glaucoma is a chronic eye disease that can lead to blindness if untreated, affecting millions globally. Early diagnosis is crucial but challenging due to the lack of early symptoms. This study focuses on using deep learning and machine learning techniques for the automatic detection of glaucoma from fundus images.

## Objectives
- To review various machine learning techniques used for glaucoma detection.
- To propose an automatic detection approach using deep convolutional neural networks (CNNs), specifically ResNet-50 and GoogLeNet models.
- To evaluate the performance of these models in classifying early and advanced glaucoma stages.

## Requirements

To run this project, you need to install and set up MATLAB and the required toolboxes and libraries.

### Prerequisites

- MATLAB R2019b or later (recommended)
- A computer with a CUDA-enabled GPU (for training deep learning models)
- MATLAB toolboxes:
  - Deep Learning Toolbox
  - Image Processing Toolbox
  - Statistics and Machine Learning Toolbox
  - Computer Vision Toolbox
  - Parallel Computing Toolbox (for GPU support)

### Installation

1. **MATLAB Installation**:
    - Download and install MATLAB from the [MathWorks website](https://www.mathworks.com/).
    - During the installation, ensure that you select the necessary toolboxes listed above.

2. **Set Up MATLAB Environment**:
    - Open MATLAB.
    - Add the project folder to the MATLAB path:
      ```matlab
      addpath('path_to_project_folder');
      ```

### MATLAB Toolboxes

Ensure the following toolboxes are installed and up-to-date:

- **Deep Learning Toolbox**: For designing and implementing deep learning models.
- **Image Processing Toolbox**: For preprocessing and augmenting images.
- **Statistics and Machine Learning Toolbox**: For implementing traditional machine learning algorithms.
- **Computer Vision Toolbox**: For computer vision tasks and functions.
- **Parallel Computing Toolbox**: For utilizing GPU capabilities to accelerate deep learning model training.

### Running the Program

To train and evaluate the models, use the relevant MATLAB scripts:

1. **Train the Models**:
    ```matlab
    trainModel('resnet50');
    trainModel('googlenet');
    ```

2. **Evaluate the Model**:
    ```matlab
    evaluateModel('resnet50');
    evaluateModel('googlenet');
    ```

## Usage

Here are some examples of how to use the project:

```matlab
% Load the trained model
model = load('path_to_model/model.mat');

% Predict using the model
results = predict(model, imread('path_to_image/image.jpg'));

% Display the results
disp(results);





