# PlantDisease-Identification

A smart farming system using deep learning and IoT to detect plant diseases efficiently and privately.  
This project integrates **Federated Learning**, **Model Pruning**, and state-of-the-art **CNN architectures** to classify diseases across 14 plant species with high accuracy thats optimized for deployment on edge devices.

---

## Project Overview

This repository contains the full implementation of:

- Plant disease classification models:
  - ResNet50
  - VGG16
  - MobileNet
  - EfficientNet-B0
  - MobileNetV3-Large
- Federated Learning for decentralized, privacy-preserving training
- Model Pruning (One-shot and Federated Pruning)
- Performance comparison across accuracy, GFLOPs, and model sparsity


## Repository Contents

- `All-Models.ipynb` – Evaluation of all five CNN models for centralized training  
- `FL-Pruning.ipynb` – Federated learning, pruning and combined FL with pruning implementation using MobileNetV3  


## Dataset

- Source: [Kaggle: New Plant Diseases Dataset (Augmented)](https://www.kaggle.com/datasets)
- Total Images: ~87,000  
- Number of Classes: 38 (14 plant species, 20 disease types)  
- Image Size: 224 × 224 px  
- Split: Train (70k), Validation (17k), Test (unused)


## Technologies

- Python, PyTorch, TensorFlow
- Federated Averaging (FedAvg)
- Cosine Annealing, LR Schedulers
- Data Augmentation, Gradient Clipping



## Citation / Acknowledgment

> The code for the implemented models and experiments is publicly available at  
> [https://github.com/shamsaht/PlantDisease-Identification](https://github.com/shamsaht/PlantDisease-Identification)


## Contributors

- [Shamsa Hamad](https://github.com/shamsaht)  
- [Shaikha Al Hosani](https://github.com/shaikha-jasem)  
- [Maryam Al Shamsi](https://github.com/alshamsi-maryam)  
MBZUAI, Abu Dhabi – IoT Course Project (ML709)


