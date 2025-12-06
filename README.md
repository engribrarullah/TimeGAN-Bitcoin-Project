# 📈 TimeGAN for Bitcoin Price Synthesis

## 📌 Project Overview
This project implements a **Time-series Generative Adversarial Network (TimeGAN)** to generate realistic synthetic data for Bitcoin cryptocurrency markets. The model captures the temporal dynamics of historical Bitcoin prices (Open, High, Low, Close, Volume) and learns to produce new sequences that statistically resemble the real data.

This work was conducted as part of the **BDA Comprehensive Evaluation Project (CEP) 2025**.

## 📂 Repository Structure
- **`TimeGAN_Implementation.ipynb`**: The complete source code including data preprocessing, TimeGAN architecture (Embedder, Generator, Discriminator, Recovery), training loops, and evaluation metrics.
- **`DATASET_LINK.txt`**: Contains the Google Drive link to download the high-resolution `bitcoin.csv` dataset used in this project.

## 🚀 How to Run
1. Open the `.ipynb` notebook in **Google Colab**.
2. Download the dataset from the link provided in `DATASET_LINK.txt`.
3. Upload the `bitcoin.csv` file to your Colab runtime or mount your Google Drive.
4. Run the cells sequentially to train the model and generate synthetic data.

## 📊 Results & Evaluation
The project evaluates the quality of synthetic data using:
- **Visual Analysis**: PCA and t-SNE plots to visualize distribution overlap.
- **Discriminative Score**: How well a classifier can distinguish real vs. synthetic data.
- **Predictive Score (TSTR)**: Training a predictor on synthetic data and testing it on real data.

## 👥 Authors
- **Muhammad Fahim**
- **Ibrar Ullah**
- **Abdul Wasey**
- **Rozi Khan**

---
*Department of Software Engineering, Quetta, Pakistan.*
