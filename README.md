# improc_cv_final_assignment

The notebook is programmed first in Google Colab. [Here is the link](https://colab.research.google.com/drive/1l8dtlRAJwVKPg7OcpjDUVPdBpGkO1hKJ?usp=sharing)

This repository is made to complete image processing and computer vision final assignment.

## Data
The data consists of skin lesion images with categories:

1. None
2. Melanoma
3. Seborrheic keratosis

These categories have been labeled in the csv file

## Objective
The objectives are:

1. Load the data of images with corresponding image id
2. Extract features with descriptor
    1. Task 1: Extract geometrical/mophological descriptor using segmented images
    2. Task 2: Extract texture descriptor using original and superpixel images
    3. Task 2a (optional): Combine original image with existing superpixel imag
    4. Task 2b (optional): Make a superpixel from original image and combine them
3. Classify image
