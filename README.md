# Polyp-Segmentation-in-Colonoscopy-Images-using-U-Net

# Polyp Segmentation using U-Net

This project focuses on **automatic polyp segmentation** from colonoscopy images using a **U-Net architecture** implemented in TensorFlow/Keras. Accurate segmentation of polyps is crucial for **early detection and diagnosis of colorectal cancer**.

## Features
- Preprocessing and augmentation using **Albumentations** library.
- U-Net model with customizable encoder-decoder structure.
- Evaluation using **Dice Coefficient, IoU, and Accuracy**.
- Visualization of predictions with overlays on original images.
- Custom loss function combining **Binary Crossentropy + Dice Loss**.

## Dataset
- Dataset used: **Kvasir-SEG** (Publicly available colonoscopy polyp dataset).

## How to Use
1. Load the Notebook (`.ipynb`) to train or predict.
2. Use the pre-trained model (`.h5`) for inference on new images.
3. Visualize predictions and metrics directly in the Notebook.

## Requirements
- Python 3.x
- TensorFlow / Keras
- OpenCV
- Albumentations
- Matplotlib, Seaborn
- Uumpy, Pandas
- Os
- Sklearn
