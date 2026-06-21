# Brain Tumor MRI Dataset

## Description
This directory should contain the dataset used for training the brain tumor segmentation and classification models.
The dataset consists of T1, T2, and FLAIR weighted contrast-enhanced MRI images, with accompanying pixel-level binary masks for tumor segmentation and categorical folder splits for tumor classification.

## Download Link
The dataset is publicly available. You can download the dataset from [Kaggle's Brain Tumor MRI Dataset](https://www.kaggle.com/). 

## Expected Structure
Please extract the dataset such that it follows this structure:

```
Dataset/
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── pituitary/
│   └── notumor/
├── Testing/
│   ├── glioma/
│   ├── meningioma/
│   ├── pituitary/
│   └── notumor/
└── masks/ (If you are using semantic segmentation)
    ├── img1_mask.png
    └── img2_mask.png
```

*Note: Since semantic segmentation requires mask images, if the public dataset does not contain masks, pseudo-masks must be generated using classical image processing techniques like OpenCV thresholding.*
