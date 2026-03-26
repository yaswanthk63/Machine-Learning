# Visualizing CNN Feature Maps: Understanding Deep Learning Representations

##  Overview
This project explores how Convolutional Neural Networks (CNNs) learn internal representations by visualizing feature maps at different layers.

Unlike traditional image classification projects, this work focuses on **model interpretability**, revealing how convolutional filters respond to input data.

---

##  Objectives

- Understand how CNNs extract hierarchical features  
- Visualize feature maps across multiple layers  
- Compare shallow vs deep representations  
- Improve interpretability of deep learning models  

---

##  Dataset

The project uses the MNIST dataset, consisting of grayscale handwritten digit images (0–9).  
Its simplicity makes it ideal for analyzing feature extraction behaviour.

---

##  Methodology

### 1. Data Preparation
- Normalization of pixel values  
- Reshaping for CNN input  

### 2. CNN Architecture
- 3 convolutional layers  
- Progressive feature extraction  
- Fully connected classification layer  

### 3. Feature Map Extraction
- Intermediate outputs captured using a secondary model  
- Visualization of activations at each layer  

---

##  Visualizations

This project includes:

- Input image visualization  
- Feature maps (Layer 1, Layer 2, Deep layer)  
- Grid visualization of all filters  

All plots are generated using **color-blind friendly colormaps (cividis)** for accessibility.
