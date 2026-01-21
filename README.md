🧠 Intelligent Image Quality Assessment and Automatic Enhancement
📌 Project Overview

This project focuses on designing an intelligent Computer Vision system that automatically detects image quality degradation (such as blur, noise, and low contrast) and applies appropriate Digital Signal & Image Processing (DSIP) techniques to enhance the image quality.

Unlike traditional image enhancement approaches that rely on manual parameter tuning, this system performs analysis-driven enhancement, making it adaptive and scalable.

🎯 Objectives

To analyze images as 2D signals using DSIP principles

To automatically detect image degradation (blur, noise, low contrast)

To apply suitable image enhancement techniques based on detected degradation

To visually and quantitatively evaluate enhancement performance

🔬 Methodology

The system follows a structured Computer Vision pipeline:
Input Image
↓
Preprocessing
↓
Image Quality Analysis
   - Blur Detection (Laplacian Variance)
   - Noise Estimation
   - Contrast Analysis
↓
Decision Engine
↓
Adaptive Image Enhancement
↓
Enhanced Output Image

🧠 DSIP Concepts Used

Image as a digital signal (sampling & quantization)

Spatial filtering and convolution

Frequency-domain analysis (edge and sharpness estimation)

Histogram-based contrast analysis

High-boost filtering and unsharp masking

🛠️ Techniques Implemented
🔹 Degradation Detection

Blur Detection: Laplacian variance

Noise Estimation: Statistical standard deviation

Contrast Analysis: Intensity range evaluation

🔹 Image Enhancement

Blur Correction: Unsharp masking / High-boost filtering

Noise Removal: Median and Gaussian filtering

Contrast Enhancement: Histogram Equalization / CLAHE

📊 Evaluation (Current / Planned)

Visual comparison (before vs after enhancement)

Planned integration of:

PSNR (Peak Signal-to-Noise Ratio)

SSIM (Structural Similarity Index)

🧰 Tools & Technologies

Python

OpenCV

NumPy

Matplotlib

Jupyter Notebook / Google Colab


🚀 Current Status

✔ Automatic blur detection implemented

✔ Blur correction using unsharp masking completed

⏳ Noise and contrast modules in progress

⏳ Quantitative evaluation metrics to be added

🔮 Future Scope

Multi-degradation handling (blur + noise together)

Machine learning–based degradation classification

Real-time image/video enhancement

Integration with deep learning models

Deployment as a lightweight application or API

📖 Academic Relevance

This project serves as a strong application of Digital Signal & Image Processing concepts in Computer Vision, making it suitable for academic evaluation, research-oriented learning, and future extension into AI-based systems.

👤 Author

Atharva Shinde
B.Tech – Computer Science (AI & ML)
DSIP Project
