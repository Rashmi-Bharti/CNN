# Skin Disease Classification Using Custom CNN

## Overview
This project aims to build a CNN model to classify 9 different types of skin diseases, including Melanoma, using a custom convolutional neural network (CNN) architecture. The dataset consists of 2357 images categorized into 9 classes.

## Project Pipeline
1. **Data Preprocessing**: Loaded and resized images, normalized pixel values, and visualized sample images.
2. **Initial Model**: Built a simple CNN architecture and trained the model for 20 epochs.
3. **Evaluation**: Identified overfitting, applied data augmentation to resolve it.
4. **Class Imbalance**: Addressed imbalanced class distribution using the `Augmentor` library.
5. **Final Model**: Retrained the model with balanced data and data augmentation.

## Results
- The model achieved an accuracy of X% after balancing the dataset and applying data augmentation.
- Addressed overfitting using data augmentation techniques.

## Instructions to Run
1. Clone the repository.
2. Install required dependencies using `pip install -r requirements.txt`.
3. Run the notebook in a GPU environment for faster training.

## Dataset
The dataset was provided by the International Skin Imaging Collaboration (ISIC).
