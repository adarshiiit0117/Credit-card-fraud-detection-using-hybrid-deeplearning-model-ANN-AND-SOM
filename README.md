# Credit-card-fraud-detection-using-hybrid-deeplearning-model-ANN-AND-SOM
# 🧠 Credit Card Fraud Detection with ANN & Self-Organizing Maps

This project applies both **Self-Organizing Maps (SOM)** for unsupervised anomaly detection and **Artificial Neural Networks (ANN)** for supervised learning on credit card transaction data to identify potential frauds.

## 📁 Files

- `credit_card_fraud.ipynb` – Main Jupyter Notebook with the full workflow.
- `Credit_Card_Applications.csv` – Credit card transaction dataset (Kaggle).

## 📌 Approach

1. **Preprocessing**
   - Feature scaling
   - Normalization of transaction data

2. **SOM (Self-Organizing Map)**
   - Unsupervised learning to identify anomalous transactions
   - Visualize potential frauds in a 2D map

3. **ANN (Artificial Neural Network)**
   - Train a binary classifier to predict fraud based on SOM results
   - Evaluate performance on labeled data

## 🔧 Installation

```bash
pip install minisom
pip install tensorflow
