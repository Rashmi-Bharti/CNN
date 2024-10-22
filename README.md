# Skin Disease Classification Using Custom CNN

## Overview
This project aims to build a CNN model to classify 9 different types of skin diseases, including Melanoma, using a custom convolutional neural network (CNN) architecture. Melanoma accounts for 75% of skin cancer deaths, making early detection critical.

## Problem Statement
To build a CNN-based model that accurately detects melanoma and other skin diseases, providing dermatologists with an automated evaluation tool. The dataset consists of 2357 images sourced from the International Skin Imaging Collaboration (ISIC).

## Dataset Description
The dataset includes images categorized into the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

The images were sorted according to classifications made by ISIC, with classes of melanoma and moles having slightly more dominant representation.

## Project Pipeline
1. **Data Preprocessing**: Loaded, resized images (180x180), normalized pixel values, and visualized sample images.
2. **Initial Model**: Built a simple CNN architecture and trained the model for 20 epochs.
3. **Evaluation**: Identified overfitting and applied data augmentation to resolve it.
4. **Class Imbalance**: Addressed imbalanced class distribution using the `Augmentor` library.
5. **Final Model**: Retrained the model with balanced data and data augmentation for 30 epochs.

## Results
- The model achieved an accuracy of **49.55%** after balancing the dataset and applying data augmentation.
- Overfitting was addressed using data augmentation techniques.

## Instructions to Run
1. Clone the repository.
2. Install required dependencies using `pip install -r requirements.txt`.
3. Run the notebook in a GPU environment for faster training.

## Future Work
- Explore advanced architectures and transfer learning to improve accuracy.
- Experiment with different augmentation techniques to enhance model robustness.

## Dataset
The dataset was provided by the International Skin Imaging Collaboration (ISIC). 

