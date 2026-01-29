# DnCNN Image Denoising with PyTorch
This repository contains a PyTorch impolementation of **DnCNN (Denoising Convolutional Neural Network)** for image denoising tasks.
The project utilizes the **BSDS500 (Berkeley Segmentation Dataset 500)** to train and validate the model.

## Description
The notebook implements a deep learning approach to remove noise from images. It handles the complete pipeline from data acquisition (via Kaggle) to data preprocessing and model training setup.
- **Model** : DnCNN (Denoising Convolutional Neural Network)
- **Framework** : PyTorch
- **Dataset** : BSDS500 (Berkeley Segmentation Dataset 500)

## Dataset
The Project uses the **BSDS500** dataset downloaded directly from Kaggle.
- Source : [Berkeley Segmentation Dataset 500 (BSDS500)](https://www.kaggle.com/datasets/balraj98/berkeley-segmentation-dataset-500-bsds500)
- Structure :
    - `images/train` : Training set
    - `images/test` : Test set
    - `images/val` : Validation set
    - (Note : The `ground_truth` folder is excluded as it contains segmentation maps not used for denoising.)

## Features
- Automatic dataset downloaded and extraction from Kaggle.
- Data preprocessing and loading using PyTorch `DataLoader`.
- Image visualization for training and validation samples.
- Implementation of the DnCNN architecture (implied).

