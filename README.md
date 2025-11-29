# CNN-Based Seismic Fault Detection 🚀

A deep learning project for automated detection of faults in seismic data using Convolutional Neural Networks (CNNs).
This tool assists geoscientists and interpreters by providing fast, reproducible fault extraction from seismic sections.

📌 Overview

Faults are key structural features in subsurface exploration, yet manual interpretation is time-consuming and subjective.
This project implements a CNN-based classifier to automatically detect fault vs. non-fault regions in seismic images.

Features include:

--> Seismic image preprocessing (normalization, filtering, cropping)
--> Fault/Non-fault patch extraction
--> Build/train/test CNN model
--> Visualize predictions on seismic lines
--> Performance evaluation using IoU, Accuracy, Precision, F1-score
--> Extendable pipeline for segmentation or UNet architectures

🧠 Model Architecture (CNN)

--> The model uses a lightweight CNN composed of:
--> Conv2D → ReLU → MaxPooling
--> Additional Conv layers for deeper spatial understanding
--> Dense + Dropout for classification
--> Softmax output for Fault / No-Fault prediction

This design is optimized for patch-based classification.

🛰️ Applications
--> Structural geology
--> Hydrocarbon exploration
--> Seismic interpretation QC
--> Automated pre-processing for UNet fault segmentation pipelines
--> Academic research in geophysics & ML

