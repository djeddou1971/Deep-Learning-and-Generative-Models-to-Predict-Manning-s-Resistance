# Manning's Resistance Coefficient (n) Prediction

This repository contains a Jupyter Notebook implementing **Manning’s roughness coefficient (n) prediction**
using **Deep Neural Network (DNN) ensembling** combined with **Conditional GAN (cGAN) latent-space sampling**.

## Project Structure
```
├── Manning's-Resistance-Coeficient_n_Prediction using DNN Ensembling_and_CGAN_LATENT-SAMPLING_21-11-2025.ipynb
├── requirements.txt
├── README.md
```

## Key Features
- Data preprocessing and scaling
- DNN ensemble modeling with PyTorch
- Conditional GAN (cGAN) for latent-space sampling
- Model evaluation (RMSE, MAE, R²)
- Dimensionality reduction (PCA, t-SNE)
- Explainability using SHAP and LIME
- Visualization with Matplotlib and Seaborn

## Installation
```bash
pip install -r requirements.txt
```

## Usage
Open the notebook and run all cells sequentially:
```bash
jupyter notebook
```

## Notes
GPU acceleration is recommended for training deep learning models.
