# Lung & Colon Cancer Histopathological Classification

An advanced Deep Learning project focused on the automated classification of lung and colon cancer tissues using histopathological images and Convolutional Neural Networks (CNN).

##  Project Overview
Accurate pathological diagnosis is critical for cancer treatment. This project utilizes a deep CNN architecture to distinguish between five types of tissues, including benign and various malignant carcinomas of the lung and colon, with high precision.

## Tech Stack
* **Deep Learning:** TensorFlow / Keras
* **Neural Network:** Custom CNN with Batch Normalization & Dropout.
* **Image Processing:** OpenCV, PIL, ImageDataGenerator.
* **Evaluation:** Confusion Matrix, F1-Score, ROC Curves.

##  Technical Implementation
- **Data Pipeline:** Organized over 25,000 images into structured dataframes for training, validation, and testing.
- **Model Design:** Built a Sequential model with optimized layers (Conv2D, MaxPooling2D, Flatten, and Dense).
- **Training Strategy:** Used `Adamax` optimizer and monitored performance via accuracy/loss curves.
- **Model Persistence:** Saved the final high-performing model in `.h5` format for future deployment.

## Performance & Results
- **Overall Accuracy:** 98%
- **Class-wise Precision:** Achieved near-perfect scores (0.99 - 1.00) for colon tissue types.
- **Robustness:** The model demonstrates excellent generalization on unseen medical images.

---
*Developed as part of my advanced portfolio in Medical AI and Deep Learning.*
<img width="543" height="543" alt="image" src="https://github.com/user-attachments/assets/f966ac90-76f4-4ce0-b610-e3e33e5470f9" />
