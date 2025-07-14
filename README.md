# Waste Classification Using Transfer Learning
An AI-based deep learning system for classifying waste into seven categories using pre-trained CNN models like EfficientNet, ResNet, and DenseNet.

## Table of Contents
- [About the Project](#about-the-project)
- [Datasets](#datasets)
- [Results](#demo)
- [Model Architectures](#model-architectures)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Future Work](#future-work)
- [Contributors](#contributors)
- [License](#license)

## About the Project
- This project aims to automate waste classification using deep learning. It compares eight state-of-the-art CNN models (e.g., EfficientNet-B3, ResNet-50, InceptionV3) on a combined dataset (TrashNet + TrashBox) of 16,000 images across 7 classes: paper, plastic, cardboard, metal, glass, e-waste, and medical waste.
- EfficientNet-B3 achieved the best results with 94.64% accuracy in just 11 epochs.
- The project contributes to smart waste management and supports Sustainable Development Goals (SDG 12).

## Results
| Model           | Accuracy (%) | Precision (%)  | Recall (%)  |  F1-Score (%) |
|-----------------|--------------|----------------|-------------|---------------|
| EfficientNet-B3 | 94.64        | 94.66          | 94.63       | 94.62         |
| EfficientNet-B0 | 92.61        | 93.05          | 92.22       | 92.55         |
| DenseNet-121    | 91.62        | 92.10          | 91.38       | 91.59         |
| Inception-V3    | 91.62        | 91.87          | 91.29       | 91.51         |
| MobileNet-V2    | 89.83        | 90.34          | 89.50       | 89.79         |
| ResNet-50       | 89.77        | 89.97          | 89.57       | 89.71         |
| ResNet-34       | 89.22        | 89.34          | 88.61       | 88.89         |
| VGG-16          | 88.60        | 88.63          | 88.45       | 88.49         |

![Class Distribution of Dataset](image-path-or-URL)
