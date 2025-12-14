# Human-Activity-Recognition-Dual-Stream
Deep Learning model using Dual-Stream ResNet and BiLSTM for HAR on UCI dataset.
# Human Activity Recognition using Dual-Stream ResNet-BiLSTM

## 📌 Project Overview
This project implements a **Dual-Stream Deep Learning architecture** to recognize human activities (Walking, Sitting, Standing, etc.) using the UCI HAR dataset. The model fuses **Temporal features (Raw Signals)** and **Spectral features (FFT)** to improve classification accuracy, particularly for static activities.

## 🧠 Models Implemented
1.  **Baseline 1D-CNN**: ~87.5% Accuracy
2.  **CNN-LSTM**: ~92.0% Accuracy
3.  **Proposed Dual-Stream ResNet-BiLSTM + Attention**: **96.0% Accuracy**

## 📂 Dataset
The project uses the [UCI Human Activity Recognition Using Smartphones Data Set](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones).

## 🚀 How to Run
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook `HAR_Dual_Stream_ResNet.ipynb`.
