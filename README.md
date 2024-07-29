# DL_ML_Glaucoma_Detection

# Comprehensive Review of Machine Learning and Deep Learning Techniques for Glaucoma Detection

This repository contains the source code, data, and results for the study titled "Comprehensive Review of Machine Learning and Deep Learning Techniques for Glaucoma Detection."

## Introduction
Glaucoma is a chronic eye disease that can lead to blindness if untreated, affecting millions globally. Early diagnosis is crucial but challenging due to the lack of early symptoms. This study focuses on using deep learning and machine learning techniques for the automatic detection of glaucoma from fundus images.

## Objectives
- To review various machine learning techniques used for glaucoma detection.
- To propose an automatic detection approach using deep convolutional neural networks (CNNs), specifically ResNet-50 and GoogLeNet models.
- To evaluate the performance of these models in classifying early and advanced glaucoma stages.

## Datasets
The study utilizes several public datasets, including:
- SINDI, SCES, SIMES, ARIA, DRISHTI-GS, RIM-ONE, RIGA, ORIGA-LIGHT, ACRIMA, STARE, ONHSD, and DRIVE.
- A primary dataset of 1544 fundus images categorized into no glaucoma, early glaucoma, and advanced glaucoma, augmented to 5430 images.
- The RIM-ONE dataset with 158 images for performance evaluation.

## Methodology
1. **Data Collection:** Retinal images are collected from multiple datasets.
2. **Preprocessing:** Image quality is enhanced using histogram equalization, and data augmentation techniques are applied.
3. **Feature Extraction:** Deep neural networks extract features from retinal images.
4. **Model Training:** ResNet-50 and GoogLeNet architectures are trained using the Caffe deep learning framework on a NVIDIA GeForce GTX 1080Ti GPU.
5. **Classification:** Machine learning classifiers (ANNs and SVMs) are used to classify retinal images based on extracted features.

## Implementation
The implementation involves training deep learning models using the following frameworks and tools:
- **Framework:** Caffe deep learning framework
- **Hardware:** NVIDIA GeForce GTX 1080Ti GPU

## Results
- The GoogLeNet model outperforms ResNet-50 in detecting both early and advanced stages of glaucoma.
- The combination of deep neural networks and logistic regression-based classifiers shows significant improvements in classification accuracy, sensitivity, and specificity compared to existing systems.

## Performance Evaluation
The models are evaluated based on the following metrics:
- Accuracy
- Sensitivity
- Specificity
- Area under the receiver operating characteristic (ROC) curve

## Challenges and Future Directions
- The need for large annotated datasets.
- Variability in image quality.
- Generalizability of models.
- Future research directions include improving algorithm robustness and integrating multimodal data.

## Conclusion
The proposed system accurately classifies glaucomatous retinal images using a combination of deep learning and machine learning techniques. It has the potential to enhance early detection and treatment of glaucoma, ultimately reducing the risk of blindness.

## How to Use
1. **Clone the repository:**
   ```bash
   $ git clone https://github.com/username/repository-name.git
   $ cd repository-name
