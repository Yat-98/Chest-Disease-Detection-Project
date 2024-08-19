# Chest Disease Detection and Classification

## Overview

The aim of this project is to detect and classify various chest diseases from X-ray images. Utilizing deep learning techniques, this project is designed to classify X-ray images into multiple categories such as normal, viral pneumonia, bacterial pneumonia, and others as the project evolves. This framework can be extended in the future to include additional chest diseases beyond the initial categories.

## Dataset

I have used data from the following sources:

- [Covid Chest X-ray Dataset](https://github.com/ieee8023/covid-chestxray-dataset)
- [Chest X-ray Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

The dataset currently consists of the following classes, with each class containing 133 images:

1. **Normal X-ray**
2. **Viral Pneumonia X-ray**
3. **Bacterial Pneumonia X-ray**
4. **Covid-19** (This category is included for now, but the system is designed to accommodate other chest diseases as well.)

## Project Steps

1. **Import Key Libraries and Datasets**
   - Set up the environment by importing necessary libraries and loading the datasets.

2. **Data Preprocessing**
   - Perform data cleaning, normalization, and augmentation to prepare the dataset for model training.

3. **Model Selection and Training**
   - Utilize a ResNet model to classify the X-ray images into the specified categories. Implement transfer learning to leverage pretrained models.

4. **Model Visualization**
   - Visualize the architecture of the ResNet model using TensorSpace.JS to better understand how the model processes the input data.

5. **Transfer Learning**
   - Apply transfer learning techniques to fine-tune the pretrained ResNet model for this specific classification task.

6. **Model Evaluation**
   - Assess the trained model's performance using metrics like accuracy, precision, recall, and F1-score. Visualize the confusion matrix and other relevant performance metrics.

7. **Deployment**
   - Optionally, deploy the trained model to a web application or cloud platform for real-time chest disease detection from X-ray images.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- TensorSpace.JS
- Jupyter Notebook
- Numpy, Pandas, Matplotlib, Seaborn
- Access to the X-ray datasets

## How to Use

1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python scripts to preprocess data, train the model, and evaluate performance.
4. Visualize the model architecture using TensorSpace.JS for better interpretability.
5. Assess the performance of the model and consider deployment options if desired.

## Acknowledgments

- The creators of the [Covid Chest X-ray Dataset](https://github.com/ieee8023/covid-chestxray-dataset).
- The contributors to the [Chest X-ray Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia).
- The open-source community for providing tools and resources for deep learning and data science.

