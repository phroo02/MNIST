# README

## Overview

This repository contains my solutions and experiments from the book\
**"Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow"** by
Aurélien Géron.

The notebook focuses on **image data augmentation** (shifting and
rotating MNIST digit images) and then applies these techniques to
improve the performance of a **neural network classifier**.

------------------------------------------------------------------------

## Contents

-   **Data Preparation**
    -   Loading training images and labels.\
    -   Converting between flattened arrays and 2D image format
        (`28x28`).
-   **Data Augmentation**
    -   Shifting images left, right, up, and down.\
    -   Rotating images by random angles within a given range.\
    -   Expanding the training set by combining original and augmented
        samples.
-   **Shuffling**
    -   Randomizing the dataset while keeping images and labels aligned.
-   **Model Training**
    -   Defining a simple neural network (using Keras/TensorFlow).\
    -   Training on the original dataset and evaluating performance.\
    -   Training on the **augmented dataset** to demonstrate the
        benefits of augmentation.
-   **Fine-Tuning**
    -   Adjusting hyperparameters (learning rate, batch size, epochs).\
    -   Modifying the network architecture (e.g., number of layers,
        units, dropout).\
    -   Comparing validation accuracy before and after augmentation.\
    -   Using early stopping to prevent overfitting.

------------------------------------------------------------------------

## Requirements

This project uses the following Python libraries: - `numpy` - `scipy` -
`matplotlib` - `scikit-learn` - `tensorflow` / `keras`

------------------------------------------------------------------------

## How to Run

1.  Open the notebook in Jupyter or VS Code.\
2.  Install the required libraries (see above).\
3.  Run the cells step by step to:
    -   Generate augmented data.\
    -   Train the model.\
    -   Fine-tune and evaluate performance.

------------------------------------------------------------------------

## Notes

-   The dataset used is **MNIST** (handwritten digits, 28x28 pixels).\
-   Augmentation is kept modest (±1 pixel shifts, ±15° rotations) to
    preserve digit identity.\
-   Fine-tuning steps are included to illustrate how small architectural
    or training parameter changes can improve performance.

------------------------------------------------------------------------

## Credit

This notebook is **based on exercises from the book**\
*"Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow"* by
Aurélien Géron.

All rights and credit for the original material belong to the author and
publisher.

This notebook is created **only for my personal education and practice**
--- not for redistribution or commercial purposes.
