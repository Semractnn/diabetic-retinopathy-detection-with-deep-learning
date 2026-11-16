# diabetic-retinopathy-detection-with-deep-learning

This repository contains an automated classification system for detecting **Diabetic Retinopathy (DR)** from retinal fundus images using transfer learning architectures in MATLAB.

## Project Overview
This study compares the performance of six pre-trained deep learning models using a binary classification dataset derived from the **APTOS 2019 Blindness Detection** dataset. 

- **Best Performing Model:** **EfficientNetB0** with **97.54% Accuracy** and an AUC of **0.9949**.
- **Framework & Environment:** MATLAB R2023b.

## Quick Model Comparison
| Model | Accuracy | AUC |
| :--- | :---: | :---: |
| **EfficientNetB0** | **97.54%** | **0.9949** |
| **MobileNetV2** | 96.72% | 0.9924 |
| **ResNet18** | 95.63% | 0.9949 |
| **AlexNet** | 94.54% | 0.9917 |
| **ResNet50** | 93.99% | 0.9977 |
| **VGG16** | 93.99% | 0.9814 |

## Repository Structure
- `mat_dosyalari/` — MATLAB scripts and model training files
- `gorseller/` — Performance plots, ROC curves, and confusion matrices
- `Derin Öğrenme Tabanlı Diyabetik Retinopati Tespiti.pdf` — Detailed academic paper / proceeding written in Turkish
- `bilgiler.docx` — Additional project documentation and notes

## Note on Documentation
A comprehensive academic proceeding/paper detailing the methodology, experiments, and results is included in this repository in Turkish (`Derin Öğrenme Tabanlı Diyabetik Retinopati Tespiti.pdf`).
