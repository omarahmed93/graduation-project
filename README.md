# 💊 Predicting Medical Prescriptions using Deep Learning & Image Processing

This is the official repository for my graduation project at the Arab Academy for Science, Technology & Maritime Transport (AAST). The system combines **structured patient data** and **medical image analysis** to enhance prescription prediction accuracy. By integrating deep learning with image processing, this tool supports healthcare professionals in clinical decision-making.

---

## 📌 Project Overview

The goal is to build a dual-input model that leverages both:
- **Structured data**: patient symptoms, age, and disease
- **Unstructured data**: images such as X-rays or scanned prescriptions

This allows the model to make more informed predictions and simulate a doctor's multi-modal diagnosis process.

---

## 🧠 Technologies Used

- **Python 3.9**
- **TensorFlow / Keras** – deep learning frameworks
- **OpenCV** – for image preprocessing
- **Pillow (PIL)** – for image loading and formatting
- **Pandas**, **NumPy** – data handling
- **Matplotlib**, **Seaborn** – visualization
- **Scikit-learn** – evaluation and preprocessing
- **Jupyter Notebook**

---

## 🖼️ Image Processing Module

The image processing part of the project is responsible for:

- **Loading and preprocessing** medical images (grayscale conversion, resizing, normalization)
- **Feature extraction** using Convolutional Neural Networks (CNNs)
- **Integrating image features** into the prescription prediction model

> Example use cases:
> - Extract features from chest X-rays or MRI scans
> - Analyze scanned handwritten prescriptions
> - Enhance model performance by combining visual and textual data

---

## 🗂️ Project Structure

