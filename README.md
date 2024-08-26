# Chest Disease Detection and Classification

## Introduction

Chest disease detection is a critical aspect of healthcare, especially in diagnosing conditions like pneumonia, tuberculosis, and more recently, COVID-19. With the increasing availability of medical imaging data, there is a growing need for automated solutions that can assist healthcare professionals in making accurate diagnoses quickly. This project leverages deep learning techniques to detect and classify various chest diseases from X-ray images, providing a practical and scalable solution that can be integrated into healthcare systems.

## Overview

The aim of this project is to detect and classify various chest diseases from X-ray images. Utilizing deep learning techniques, this project is designed to classify X-ray images into multiple categories such as normal, viral pneumonia, bacterial pneumonia, and others as the project evolves. This framework can be extended in the future to include additional chest diseases beyond the initial categories.

## Dataset

I have used data from the following sources:

- [Covid Chest X-ray Dataset](https://github.com/ieee8023/covid-chestxray-dataset)
- [Chest X-ray Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

The dataset currently consists of the following classes, with each class containing 133 images:

1. **Normal X-ray**
2. **Viral Pneumonia X-ray**
3. **Bacterial Pneumonia X-ray

## Model Weights

The trained model weights can be downloaded from the following link:

[Download Weights](https://drive.google.com/file/d/1mP1qjUuN0-lihfaP3UD-AqLoGko85EAC/view?usp=sharing)

After downloading, place the weights file in the `models/` directory before running the prediction or evaluation scripts.
