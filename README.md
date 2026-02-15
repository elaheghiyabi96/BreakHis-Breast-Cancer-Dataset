# BreakHis-Breast-Cancer-Dataset
A curated repository for the BreakHis Breast Cancer Histopathological Database, including folder structure, magnification levels, and class information for binary and multiclass classification tasks.
BreakHis – Breast Cancer Histopathological Database

Dataset Overview
The BreakHis dataset is designed for machine learning and deep learning tasks in breast cancer histopathology. It consists of microscopic images of breast tumor tissues, intended for both binary and multiclass classification tasks. All images in this version are resized to 224×224 pixels for compatibility with convolutional neural networks.

Total Images: 7,909
Magnification Levels: 40X, 100X, 200X, 400X
Image Format: RGB

Folder Structure

The dataset is organized into two main folders based on the classification task:

1. classificacao_binaria (Binary Classification)

Objective: Classify tumor tissues as Benign or Malignant.

Subfolders:

40X/
    benign/
    malignant/
100X/
    benign/
    malignant/
200X/
    benign/
    malignant/
400X/
    benign/
    malignant/


Each subfolder contains microscopic images corresponding to the tumor class and magnification level.

2. classificacao_multiclasse (Multiclass Classification)

Objective: Classify tumor tissues into eight different histopathological subtypes.

Subfolders:

40X/   100X/   200X/   400X/
    adenosis/
    ductal_carcinoma/
    fibroadenoma/
    lobular_carcinoma/
    mucinous_carcinoma/
    papillary_carcinoma/
    phyllodes_tumor/
    tubular_adenoma/


Each folder corresponds to a specific magnification level, containing images of each subtype.

Key Notes

The dataset can be used for experiments in image classification, deep learning, and transfer learning.

Labels are directly derived from the folder structure, making it easy to generate training and validation datasets.

The multiple magnification levels allow investigation of how scale affects classification performance.

Link: https://data.mendeley.com/datasets/jxwvdwhpc2/1
