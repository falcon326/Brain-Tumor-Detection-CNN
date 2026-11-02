# Medical Image Classification using Convolutional Neural Networks (CNN)

## Project Overview
This repository contains an end-to-end Deep Learning project developed in Python using **TensorFlow** and **Keras**. The primary objective of this model is to classify medical images to detect the presence of tumors ("yes" or "no") based on a custom image dataset. 

The pipeline covers data preprocessing, exploratory normalization, custom CNN architecture design, model training with validation tracking, and evaluation on unseen test data.

---

## Tech Stack & Libraries
* **Language:** Python
* **Deep Learning Framework:** TensorFlow, Keras
* **Data Manipulation & Evaluation:** Scikit-Learn, NumPy
* **Data Visualization:** Matplotlib
* **Environment:** Google Colab (GPU-accelerated)

---

## Model Architecture
The model is built using a Sequential API featuring multiple convolutional and pooling layers designed to extract spatial features from image data effectively:
* **Conv2D (32 filters, 3x3 kernel, ReLU)** + **MaxPooling2D**
* **Conv2D (64 filters, 3x3 kernel, ReLU)** + **MaxPooling2D**
* **Conv2D (128 filters, 3x3 kernel, ReLU)** + **MaxPooling2D**
* **Flatten Layer**
* **Dense Layer (512 units, ReLU)** + **Dropout (0.5 for regularization)**
* **Output Layer (1 unit, Sigmoid activation for binary classification)**

---

## Performance & Results
* **Training Epochs:** 15
* **Loss Function:** Binary Crossentropy
* **Optimizer:** Adam
* **Test Accuracy:** ~76% - 78%

---

## 📂 Dataset Availability
Due to GitHub's file size and file count limitations, the raw image dataset (`yes` / `no` MRI scans) is not directly hosted in this repository. 

If you would like to access the dataset for research, testing, or replication purposes, please feel free to reach out to me via email or LinkedIn.

---

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone [https://github.com/falcon326/Brain-Tumor-Detection-CNN.git](https://github.com/falcon326/Brain-Tumor-Detection-CNN.git)

2. Install the required dependencies:

   pip install -r requirements.txt

3. Open the Jupyter Notebook (.ipynb) in Google Colab or Jupyter Lab, connect your Google Drive dataset path, and run the cells sequentially.

---

👤 Author
Developed by Vildan Yılmazer

Electrical-Electronics Engineering Graduate | AI & Software Enthusiast

* **LinkedIn:** www.linkedin.com/in/vildan-yilmazer-263b52306
* **Email:** vildan.yilmazer@hotmail.com
