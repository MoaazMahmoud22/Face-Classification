# Face Detection and Classification with Multiple Architectures  

## Overview  

This project focuses on detecting and classifying faces using three distinct deep learning approaches:  

1. **RaseNet Implementation from Scratch**  
2. **DenseNet with Pre-trained Weights**  
3. **Xception with Pre-trained Weights**  

Each approach offers unique performance benefits, providing a comprehensive comparison of custom models and pre-trained architectures.  

---

## Technologies Used  

- **Python**  
- **TensorFlow/Keras**  
- **OpenCV** (for face detection preprocessing)  
- **NumPy, Pandas**  
- **Matplotlib/Seaborn** (for visualizing results)  

---

## Model Architectures  

### 1. RaseNet (From Scratch)  
A custom-built convolutional neural network with layers designed specifically for face classification.  

**Features**:  
- Multiple Convolutional layers with ReLU activation  
- Batch Normalization and Dropout for regularization  
- Fully connected dense layers for classification  

### 2. DenseNet (Pre-trained)  
DenseNet is a highly efficient convolutional network that reuses features.  

- Pre-trained on **ImageNet** for transfer learning  
- Added a custom classification head with softmax for face categories  

### 3. Xception (Pre-trained)  
The Xception model uses depthwise separable convolutions, enhancing performance and reducing computations.  

- Pre-trained weights from **ImageNet**  
- Custom classifier layer appended for fine-tuning on the face dataset  

---
