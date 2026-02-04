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

- - - - -
## DnCNN-S (DnCNN with Scheduler Comparison) Results
<img width="583" height="253" alt="스크린샷 2026-02-04 오후 5 08 55" src="https://github.com/user-attachments/assets/e2ba099c-4ccd-4fc8-976a-a8d3b3ed29b9" />

<b>fig. 1. Scheduler Comparison Results of DnCNN-S</b>

<img width="718" height="445" alt="DnCNN-S_BestResult" src="https://github.com/user-attachments/assets/e8ae3fe7-d785-4c9f-878e-8c56fbf277d9" />

<b>fig. 2. Best-5 Results of DnCNN-S</b>

- - - - -
## CDnCNN-B (DnCNN with Colord Blind Noise Image + Scheduler Comparison) Results
<img width="919" height="362" alt="CDnCNN-S_Scheduler" src="https://github.com/user-attachments/assets/739b0ffe-db80-4508-9e6f-2f9f844bfd82" />

<b>fig. 3. Scheduler Comparison Results of CDnCNN</b>


<img width="586" height="154" alt="CDnCNN-S" src="https://github.com/user-attachments/assets/6bc05932-d508-4ebe-9ced-f2275b9d4461" />

<b>fig. 4. Result of Test sample</b>

<img width="591" height="573" alt="스크린샷 2026-02-04 오후 6 00 31" src="https://github.com/user-attachments/assets/e6ca6d89-79e4-46c6-8ba7-8528851027ea" />

<img width="583" height="305" alt="스크린샷 2026-02-04 오후 6 00 46" src="https://github.com/user-attachments/assets/835b406f-cef5-4bf4-a0f2-a8b74a57bfcf" />


<img width="550" height="372" alt="스크린샷 2026-02-04 오후 6 00 51" src="https://github.com/user-attachments/assets/6fbdcdaf-b2a6-407b-adfb-6ce461d666da" />


