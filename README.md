# Riya_Soni_SelectionTask

This repository contains my submission for the Land Cover Classification task using ResNet18.

## Drive link to datasert
Link- https://drive.google.com/drive/folders/1sqwWhc6LjpW8kB5jMhKEaVtziaLcLSWM?usp=sharing

## Project Overview

## Project Overview
- Trained a CNN (ResNet18) on satellite land cover data.
- Implemented custom and torchmetrics F1 score evaluation.
- Visualized confusion matrix, training curves, and sample predictions.

## Key Files
- Riya_Soni_SelectionTask.ipynb: Main Jupyter notebook (colab).
- Riya_Soni_SelectionTask.ipynb - Colab.pdf: pdf version of main jupyter notebook to view output of cells not visible in rew notebook.
- delhi_airshed_overlay.html: Downloaded Overlay this grid (Delhi Airshed)
- labeled_dataset.csv: Labeled Dataset
- train_dataset.csv / test_dataset.csv: train-test-split
- resnet18_landcover_best.pth: Best trained model weights.
- train_losses.npy / val_losses.npy / val_accuracies.npy: Training metrics.
- Provided_Data/: Input datasets.

## Results
- Validation Accuracy: ~90%
- Early Stopping triggered at Epoch 11.
- Grassland and Water bodies showed strong classification performance.

## Author
**Riya Soni**

