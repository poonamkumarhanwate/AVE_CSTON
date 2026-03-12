# AVE_CSTON
Project 
# Requiredment 
torch
torchvision
opencv-python
numpy
matplotlib
scikit-learn
# AVE‑CSTON: Adaptive Variational Encoder with Continual Spatio‑Temporal Optimization Network

This repository contains a research‑oriented implementation for **Video Anomaly Detection**
using a **Variational Encoder + Spatio‑Temporal Conv3D Network** with an attention module.

## Supported Datasets
- UCSD Ped1 / Ped2
- CUHK Avenue

## Project Structure
```
AVE-CSTON/
│
├── datasets/
│   ├── dataset_loader.py
│
├── models/
│   ├── ave_cston_model.py
│
├── training/
│   ├── train.py
│
├── evaluation/
│   ├── test.py
│
├── visualization/
│   ├── graphs.py
│
├── utils/
│   ├── loss.py
│   ├── metrics.py
│
├── requirements.txt
└── run_training.py
```

## Install
pip install -r requirements.txt

## Train
python run_training.py
