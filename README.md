# Hand Gesture Recognition using Machine Learning

A computer vision and machine learning project that implements a **Hand Gesture Recognition** system using image classification techniques. The project utilizes the **LeapGestRecog Dataset** downloaded through the **Kaggle API** and demonstrates the complete workflow from dataset acquisition and image preprocessing to model training, evaluation, and gesture prediction.

---

# Project Overview

Hand Gesture Recognition is a fundamental application of Computer Vision that enables machines to interpret human hand movements and gestures.

Gesture recognition systems are widely used in:

- Human-Computer Interaction (HCI)
- Sign Language Recognition
- Virtual Reality
- Robotics
- Smart Automation
- Touchless User Interfaces

This project builds an image classification model capable of recognizing different hand gestures using the **LeapGestRecog Dataset**.

---

# Problem Statement

Traditional interaction methods rely heavily on physical input devices such as keyboards and mice.

The objective of this project is to develop a machine learning model capable of recognizing hand gestures directly from images, enabling more natural and intuitive human-computer interaction.

---

# Dataset

This project uses the **LeapGestRecog Dataset** available on Kaggle.

> **Note:** The dataset is **not included** in this repository because of GitHub's file size limitations.

---

## Download Dataset using Kaggle API

Install Kaggle

```bash
pip install kaggle
```

Configure your Kaggle API credentials (`kaggle.json`) and run:

```bash
kaggle datasets download -d gti-upm/leapgestrecog
```

Extract the downloaded ZIP file before running the notebook.

Alternatively, the dataset can be downloaded directly from Kaggle:

https://www.kaggle.com/datasets/gti-upm/leapgestrecog

---

# Dataset Structure

```
leapGestRecog/

├── 00/
├── 01/
├── 02/
├── ...
└── 09/
```

Each folder contains images representing different hand gestures.

---

# Project Objectives

- Download dataset using Kaggle API
- Load gesture images
- Perform image preprocessing
- Train an image classification model
- Predict hand gestures
- Evaluate model performance
- Test the model on unseen gesture images

---

# Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle API
- Jupyter Notebook

---

# Repository Structure

```
SCT_ML_4/

│
├── Hand_gesture_recognition.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── images/
```

---

# Machine Learning Workflow

### 1. Install Kaggle API

Install the Kaggle package and configure the API credentials.

### 2. Download Dataset

Download the LeapGestRecog dataset directly from Kaggle using the Kaggle API.

### 3. Load Images

Read gesture images from the dataset.

### 4. Image Preprocessing

- Resize images
- Convert to grayscale (if applicable)
- Normalize pixel values
- Convert images into feature vectors

### 5. Train-Test Split

Split the dataset into training and testing sets.

### 6. Model Development

Train the machine learning classifier using the processed gesture images.

### 7. Model Evaluation

Evaluate the trained model using classification metrics.

### 8. Gesture Prediction

Predict hand gestures for new input images.

---

# Dataset Download (Kaggle API)

```bash
pip install kaggle

kaggle datasets download -d gti-upm/leapgestrecog

unzip leapgestrecog.zip
```

After extracting the dataset, update the dataset path inside the notebook before running all cells.

---

# Model Evaluation

The trained model is evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

These metrics measure the overall classification performance on unseen gesture images.

---

# Results

The trained model successfully recognizes multiple hand gestures from input images after preprocessing and feature extraction.

The notebook demonstrates predictions on unseen gesture images together with model evaluation metrics.

---

# Future Improvements

- Convolutional Neural Networks (CNN)
- Transfer Learning
- TensorFlow/Keras Implementation
- Real-Time Gesture Recognition
- Webcam Integration
- MediaPipe Hand Tracking
- Streamlit Deployment

---

# Skills Demonstrated

- Computer Vision
- Image Classification
- Image Preprocessing
- Feature Extraction
- Machine Learning
- Kaggle API Integration
- OpenCV
- Python Programming
- Scikit-learn

---

# Installation

Clone the repository

```bash
git clone https://github.com/dipanshushende/SCT_ML_4.git
```

Navigate to the project directory

```bash
cd SCT_ML_4
```

Install dependencies

```bash
pip install -r requirements.txt
```

Download the dataset using the Kaggle API

```bash
kaggle datasets download -d gti-upm/leapgestrecog
```

Extract the dataset and update the dataset path inside the notebook.

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Hand_gesture_recognition.ipynb
```

Run all notebook cells sequentially.

---

# Repository

GitHub Repository

https://github.com/dipanshushende/SCT_ML_4

---

# Author

**Dipanshu Shende**

Machine Learning Enthusiast | Python Developer | Data Science Learner

GitHub

https://github.com/dipanshushende

---

# Acknowledgements

- SkillCraft Technology – Machine Learning Internship
- Kaggle
- LeapGestRecog Dataset
- OpenCV Documentation
- Scikit-learn Documentation

---

# License

This project has been developed for educational purposes as part of the **SkillCraft Technology Machine Learning Internship**.

---

⭐ **If you found this project useful, consider giving it a Star!**
