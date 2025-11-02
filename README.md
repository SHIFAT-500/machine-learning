# 🧠 Multiclass Tumor Detection Using Deep Learning

## 📘 Overview

This project focuses on detecting **different types of brain tumors** from MRI images using **deep learning-based classification models**. The notebook implements preprocessing, model training, evaluation, and visualization steps to classify tumor types effectively.

The goal of this project is to **automate the diagnosis process** and assist medical professionals in identifying brain tumor categories more accurately and efficiently.

---

## 🧩 Features

* Image preprocessing and data augmentation
* Deep learning model implementation using TensorFlow/Keras
* Multi-class classification (e.g., glioma, meningioma, pituitary tumor, and no tumor)
* Visualization of training metrics (accuracy, loss)
* Model evaluation with confusion matrix and classification report

---

## 🧠 Model Architecture

The project utilizes a **Convolutional Neural Network (CNN)** architecture designed for image classification.
Main components:

* Convolutional + MaxPooling layers
* Dropout for regularization
* Dense layers with softmax activation for multi-class output

You can modify or extend the model to use advanced architectures like **VGG16**, **ResNet50**, or **EfficientNet** for improved performance.

---

## 🧰 Technologies Used

* **Python 3.x**
* **TensorFlow / Keras**
* **NumPy**
* **Matplotlib**
* **scikit-learn**
* **OpenCV / PIL**

---

## 📂 Dataset

The dataset contains MRI images categorized into multiple tumor types:

* **Glioma**
* **Meningioma**
* **Pituitary**
* **No Tumor**

If you are using a public dataset, mention the source here (e.g., [Kaggle Brain Tumor MRI Dataset](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri)).

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/<your-username>/multiclass-tumor-detection.git
   cd multiclass-tumor-detection
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook "multiclass tumor detection using deep learning.ipynb"
   ```
4. Run all cells to train and evaluate the model.

---

## 📊 Results

* Achieved high accuracy in classifying tumor types.
* Model performance evaluated using:

  * Accuracy score
  * Confusion matrix
  * Classification report

(You can add screenshots of accuracy/loss graphs or confusion matrices here.)

---

## 📈 Future Work

* Integrate Grad-CAM for tumor region visualization
* Experiment with transfer learning models (VGG, ResNet, EfficientNet)
* Deploy the model as a web application using Streamlit or Flask

---

## 👨‍💻 Author

**MD Shifat Hossain**
**MD Parvez Hosen**
**Md Mehedi Hasan Jony**
University Project — *Multiclass Tumor Detection Using Deep Learning*
📧 Contact: shifathossain870@gmail.com
📧 Contact: parvezmosherraf77@gmail.com

---

## ❤️ Acknowledgements

Special thanks to:

* Dataset contributors on Kaggle
* TensorFlow/Keras open-source community
* Academic mentors and teammates for guidance
