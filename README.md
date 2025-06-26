# Project IV – Deep Learning - Computer Vision 🧠📷

This repository contains the work for **Project IV** of the Data Science Master's program at Nuclio Digital School. The focus of this project is on **image classification** using **deep learning** techniques with the **CIFAR-10 dataset**.

## 🎯 Objective

Train and evaluate **10 different neural network configurations** to compare their performance and reach a minimum of **80% test accuracy** (not training or validation accuracy).

## 📂 Dataset

- **Name:** CIFAR-10 (available via `keras.datasets`)
- **Images:** 50,000 for training and 10,000 for testing
- **Format:** RGB, 32x32 pixels
- **Classes:** 10 labeled categories

## ⚙️ Project Requirements

This project includes **10 distinct experiments**, all implemented within a **single Jupyter Notebook**, by modifying:

- Neural network architecture (layers, neurons, filters)
- Optimizers and learning rate
- Batch size and training strategies
- Overfitting control methods (Dropout, EarlyStopping, Regularization)
- Advanced techniques such as **Data Augmentation** and **Transfer Learning**

> 🔸 Each configuration is treated as a separate model and analyzed individually.

## 🚫 Not considered valid experiments:

- Running the sample model without changes (considered project 0)
- Simply increasing the number of epochs
- Using EarlyStopping as the only change

## 📊 Evaluation Criteria

Each experiment includes:

- A documented architectural or hyperparameter change
- A clear analysis of the outcome (better or worse)
- Justification of decisions
- A **final summary comparison** across all 10 models
- At least one model above 80% accuracy

## 📊 Results Summary

The project demonstrates a clear **evolution in model performance** across 10 experiments:

- **Initial models** (Projects 1–3) were used to establish a baseline but showed signs of overfitting and lacked sufficient accuracy.
- **Mid-range experiments** (Projects 4–6) introduced architectural tuning, BatchNormalization, and dynamic learning rates, leading to **gradual improvements**.
- In **Project 7**, the model surpassed the target **80% test accuracy** with improved generalization and minimal overfitting.
- **Data Augmentation** was introduced and refined in Projects 8–10, leading to the **best performing model** in Project 10, which showed:
  - Higher validation accuracy than training accuracy
  - Smooth loss curves with no strong overfitting
  - Strong and stable generalization performance

The final configuration successfully balances model complexity, training stability, and test accuracy.

These results can be analized in the document: Albert_Fernandez_ProyectoIV_Deep_Learning.pdf

## 🚀 How to Run

1. Install required dependencies:

```bash
pip install tensorflow keras matplotlib numpy
