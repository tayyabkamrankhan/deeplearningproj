# IP102 Agricultural Pest Classification - Baseline Reproduction

This repository contains the reproduced baseline model for the paper "Deep learning based agricultural pest monitoring and classification" (Venkateswara & Padmanabhan, 2025). This is part of Assignment 02.

## Dataset
We use the IP102 dataset containing over 75,000 images across 102 pest categories. 
* **Download**: [IP102 Official GitHub](https://github.com/xpwu95/IP102)
* **Structure**: Ensure images are placed in `./IP102_Dataset/` grouped by class folders.

## Setup Instructions
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Download the dataset and place it in the root directory.
4. Run `Baseline_Implementation.ipynb` via Jupyter or Google Colab.

## Model Configuration
* **Architecture**: CNN (ResNet18 backbone) with custom classifier.
* **Regularization**: Batch Normalization, Dropout (0.5), and Early Stopping.
* **Split**: 70% Training / 30% Testing.
