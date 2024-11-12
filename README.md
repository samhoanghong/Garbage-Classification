# Garbage-Classification

This repository contains a garbage classification system using a multimodal approach with ResNet-50 and BERT to classify images into four categories: blue, green, black, and ttr, utilizing both images and text descriptions from file names.

  - Transform_data_structure.ipynb: Handles text preprocessing and data restructuring. This notebook creates three CSV files for training, validation, and testing datasets, each containing three columns: description, image path, and class. The CSV files are saved under Home/dataset, and all images are stored in the images folder within this directory.
    
  - main.ipynb: The primary notebook for training and testing the model.

  - Data_analysis.ipynb: Used for exploratory data analysis (EDA) and testing predictions, featuring figures, tables, and explanations.
    
Additionally, the Home/dataset/results directory stores a JSON file with testing metrics.
