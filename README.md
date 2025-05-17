# 🩸 Fingerprint-Based Blood Group Classification using CNN

This project leverages Convolutional Neural Networks (CNN) to classify **8 blood groups** from **fingerprint images**. It uses a publicly available dataset from Kaggle and is deployed using Flask for real-time predictions via a web interface.

## 📁 Folder Structure

├── pycache/ # Python cache files

├── dataset/ # Kaggle dataset (contains fingerprint images)

├── executed output/ # Executed video of the project

├── templates/ # HTML templates for the Flask web interface

├── app.py # Flask app for deployment

├── blood_group_cnn_model.h5 # Trained CNN model file

├── data_preprocessing.py # Script for data cleaning, resizing, splitting

├── evaluate.py # Evaluation script for testing the model

├── requirements.txt # Python dependencies

├── train_model.py # Script to train the CNN model


---

---

## 📥 Dataset

- **Source**: [Kaggle - Fingerprint Blood Group Detection](https://www.kaggle.com/datasets/abhiramshibaraya/fingerprint-based-blood-group-detection)
- **Classes**:
  - A+, A-, B+, B-, AB+, AB-, O+, O-
- **Preprocessing**: Resized all images to **128x128**

---

## 🧠 Model

- **Architecture**: CNN
- **Layers**: Conv2D, MaxPooling, Dropout, Dense
- **Loss Function**: Categorical Crossentropy
- **Optimizer**: Adam
- **Frameworks**: TensorFlow/Keras

---

## 📊 Performance

| Metric      | Score |
|-------------|-------|
| Accuracy    | 0.98  |
| Precision   | 0.98  |
| Recall      | 0.97  |
| F1-Score    | 0.975 |

✅ The model shows high reliability in classifying all 8 blood groups.

---

## 🌐 Web App – Output

Once the Flask app is running:

1. Upload a fingerprint image.
2. The model processes the image.
3. The app **predicts and displays the blood group**.

---

**🙌 Credits**

Dataset: Kaggle – Fingerprint Blood Group Detection

Developed by: SarikaSowmya Munagavalasa



