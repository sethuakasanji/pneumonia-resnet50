# PneumoniaMNIST - ResNet-50 Fine-Tuning

This project fine-tunes a pretrained ResNet-50 to distinguish pneumonia from normal chest X-rays using the PneumoniaMNIST dataset.

## Dataset
[PneumoniaMNIST on Kaggle](https://www.kaggle.com/datasets/rijulshr/pneumoniamnist/data)

## How to Run

1. Upload the dataset file (`pneumoniamnist.npz`) to Google Colab.
2. Open the notebook: `pneumonia_resnet50_colab.ipynb`
3. Run all cells sequentially.

## Evaluation Metrics
- **Accuracy**: 0.9350
- **Precision**: 0.9102
- **Recall**: 0.9617

## Results
Model generalizes well and handles class imbalance using data augmentation and robust evaluation.
