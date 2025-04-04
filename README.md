# 🎓 Bachelor's Thesis - Time series forecasting as image reconstruction using U-Net

**Thesis Title:** *Forecasting come Image Reconstruction: un approccio basato sull'architettura U-Net*  
**Degree:** BSc in Statistical Sciences for Big Data
**University:** Università degli Studi di Salerno
**Academic Year:** 2023/2024

---

## 📌 Project Overview

This thesis proposes a novel approach to time series forecasting by reframing it as an **image reconstruction task** using **deep learning**. Instead of traditional numeric-based forecasting models, this work leverages image-based methods by converting time series data into 2D representations.

---

## 🔬 Methodology

1. **Data Transformation**  
   Time series are converted into images using:
   - **GASF** (Gramian Angular Summation Field)
   - **GADF** (Gramian Angular Difference Field)
   - **MTF** (Markov Transition Field)

2. **Model Architecture**  
   - Custom **U-Net** models were trained for each image representation.
   - Models were designed to perform **forecasting as image reconstruction**.

3. **Comparison Baseline**  
   - A traditional **autoregressive (AR)** statistical model was implemented as a benchmark.

---

## 📊 Evaluation Metrics

- **Forecasting Accuracy:**
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
- **Image Quality:**
  - Peak Signal-to-Noise Ratio (PSNR)
  - Structural Similarity Index Measure (SSIM)

---

## 🏆 Key Results

- The **GASF-based U-Net** model outperformed other deep learning models in terms of image quality.
- The **AR model** was superior in pure forecasting accuracy (lower MSE and MAE).
- The best model depends on the target: visual quality vs. numerical accuracy.

---

## 🚀 Future Work

The thesis outlines several directions for improving deep learning performance:
- Enlarging the dataset
- Reducing prediction windows
- Exploring advanced architectures like **Transformers** and **Diffusion Models**

---
