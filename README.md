# Image Classification - Multiclass Intel Dataset

## Overview
This project is a deep learning-based image classification model using TensorFlow and Keras. It explores dataset structure, preprocesses images, and builds a CNN model to classify images into different categories.

## Dataset
The dataset consists of images categorized into six different classes:
- **Buildings**
- **Forest**
- **Glacier**
- **Mountain**
- **Sea**
- **Street**

The dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification).

## Features
- **Data Exploration**: Displays sample images and class distributions.
- **Data Preprocessing**: Converts images into TensorFlow datasets, normalizes pixel values.
- **Model Building**: Uses CNN layers for image classification.
- **Model Training**: Trains with validation splitting and monitors performance.
- **Evaluation**: Evaluates accuracy and generates performance metrics.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Artin-Rh/Image-Classification-Multi-class-Intel-Dataset.git
   cd Image-Classification-Multi-class-Intel-Dataset
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the dataset following the steps in the **Dataset** section.

## Usage
Run the Jupyter Notebook:
```bash
jupyter notebook Intel_Image_Classification.ipynb
```

## Dependencies
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Seaborn
- Kaggle API (for dataset download)

## Future Improvements
- Hyperparameter tuning
- More data augmentation techniques
- Experimenting with different CNN architectures

