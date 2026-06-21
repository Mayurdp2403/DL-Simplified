# Model Implementations for Brain Tumor Segmentation & Classification

This repository directory contains the implementation of the end-to-end deep learning framework that takes MRI brain scans, performs precision semantic segmentation, and subsequently classifies the tumor type (Glioma, Meningioma, Pituitary).

## Architectures Implemented

1. **Custom CNN Backbone + Vanilla U-Net**: Built from scratch to establish a baseline segmentation boundary performance.
2. **ResNet50 + U-Net (Transfer Learning)**: Leveraging a pre-trained ResNet50 encoder path for enhanced structural feature extraction.
3. **VGG16 Custom Classifier**: A multi-class classification model trained strictly on bounded region crops to isolate tumor types.
4. **ResNet101 Unified Multi-Task Network**: An advanced baseline attempting simultaneous segmentation mask output and category prediction.

## Usage Guide

To run the pipeline locally or on Kaggle/Colab:
1. Ensure your Python environment has the dependencies from `requirements.txt` installed.
2. Ensure you have downloaded the dataset and placed it in `../Dataset/` following the required structure.
3. Open `brain_tumor_pipeline.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab.
4. Run all cells sequentially.

## Evaluation Metrics
- **Classification**: Sparse Categorical Cross-Entropy loss, Accuracy, Precision, Recall, and F1-Score.
- **Segmentation**: Dice Coefficient, Intersection over Union (IoU), and Binary Cross-Entropy loss.
