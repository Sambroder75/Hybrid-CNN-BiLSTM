# Hybrid-CNN-BiLSTM
Detection of Zero-Day Attacks in SDN using Hybrid CNN-BiLSTM.

# Hybrid CNN-BiLSTM for Zero-Day Intrusion Detection

## 📌 Project Overview
This project proposes a Hybrid Deep Learning model combining **1D-CNN** (Spatial Feature Extraction) and **BiLSTM** (Temporal Sequence Analysis) to detect Zero-Day attacks in Software-Defined Networking (SDN).

## 📊 Results
- **Overall Accuracy:** 99.98%
- **Zero-Day Detection (U2R & Botnets):** 100% Recall
- **Dataset Used:** InSDN 2021

## 📂 Dataset
The dataset used is the **InSDN 2021** dataset.
Due to file size limits, the cleaned dataset (`InSDN_Cleaned.csv`) is hosted externally.
👉 **[Download Dataset Here](https://drive.google.com/drive/folders/1uXdr1e0jGVMyBduBWZeOHel26fYimn0X)**

## 🖼️ Performance Visualizations
### Training Stability
![Training Curves](training_curves%20(3).png)

### Confusion Matrix
![Confusion Matrix](confusion_matrix%20(3).png)

## 🚀 How to Run
1. Download the `InSDN_Cleaned.csv` from the link above.
2. Open the `.ipynb` notebook in Google Colab.
3. Upload the dataset to your Colab session.
4. Run all cells.
