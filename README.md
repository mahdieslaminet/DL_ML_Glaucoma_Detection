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


EXTRACTED LINKS OF CONTENT:

https://doi.org/10.1016/j.health.2023.100140
https://www.elsevier.com/locate/health
http://www.elsevier.com/locate/health
http://crossmark.crossref.org/dialog/?doi=10.1016/j.health.2023.100140&domain=pdf
mailto:rohitthanki9@gmail.com
https://doi.org/10.1016/j.health.2023.100140
http://creativecommons.org/licenses/by-nc-nd/4.0/
https://www.who.int/blindness/causes/priority/en/
https://www.who.int/blindness/causes/priority/en/
https://www.who.int/blindness/causes/priority/en/
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb2
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb2
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb2
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb3
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb3
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb3
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb3
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb3
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb4
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb4
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb4
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb4
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb4
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb4
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb4
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb5
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb5
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb5
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb5
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb5
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb6
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb6
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb6
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb6
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb6
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb7
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb7
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb7
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb8
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb8
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb8
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb9
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb9
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb9
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb9
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb9
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb10
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb10
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb10
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb11
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb11
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb11
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb11
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb11
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb12
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb12
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb12
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb12
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb12
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb13
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb13
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb13
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb13
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb13
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb13
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb13
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb14
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb14
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb14
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb14
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb14
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb15
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb15
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb15
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb15
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb15
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb16
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb16
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb16
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb16
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb16
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb17
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb17
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb17
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb17
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb17
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb18
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb18
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb18
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb18
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb18
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb19
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb19
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb19
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb20
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb20
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb20
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb21
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb21
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb21
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb21
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb21
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb22
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb22
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb22
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb22
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb22
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb23
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb23
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb23
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb24
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb24
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb24
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb24
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb24
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb25
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb25
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb25
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb25
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb25
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb26
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb26
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb26
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb26
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb26
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb27
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb27
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb27
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb27
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb27
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb28
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb28
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb28
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb28
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb28
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb29
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb29
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb29
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb30
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb30
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb30
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb30
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb30
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb31
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb31
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb31
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb31
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb31
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb32
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb32
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb32
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb32
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb32
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb33
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb33
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb33
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb33
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb33
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb33
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb33
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb34
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb34
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb34
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb35
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb35
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb35
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb36
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb36
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb36
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb36
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb36
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb36
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb36
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb37
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb37
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb37
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb37
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb37
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb38
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb38
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb38
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb38
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb38
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb39
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb39
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb39
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb39
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb39
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb40
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb40
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb40
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb40
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb40
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb41
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb41
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb41
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb41
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb41
http://pages.cs.wisc.edu/~bolo/shipyard/neural/local.html
http://pages.cs.wisc.edu/~bolo/shipyard/neural/local.html
http://pages.cs.wisc.edu/~bolo/shipyard/neural/local.html
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb43
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb44
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb44
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb44
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb45
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb45
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb45
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb46
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb46
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb46
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb46
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb46
http://arxiv.org/abs/1602.07360
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb48
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb48
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb48
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb49
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb49
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb49
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb49
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb49
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb49
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb49
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb50
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb50
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb50
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb50
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb50
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb51
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb51
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb51
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb51
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb51
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb51
http://refhub.elsevier.com/S2772-4425(23)00007-2/sb51







