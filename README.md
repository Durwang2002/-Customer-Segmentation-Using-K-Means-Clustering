# 🌿 Crop Disease Identification using Deep Learning

This project is a user-friendly web app that helps farmers and agricultural researchers identify crop diseases from images of plant leaves. It uses a deep learning model (Convolutional Neural Network) trained on the PlantVillage dataset to classify 38 different crop disease classes, including healthy leaves.

Built with Flask for the backend and a clean HTML interface, the app allows users to upload an image, view predictions, get detailed information about the disease, and explore preventive measures—all in one place.

---

## 🚀 Features

- Upload crop leaf images from your device.
- Detect diseases from 38 classes using a trained CNN model.
- Shows prediction confidence.
- Displays disease name, description, symptoms, precautions, and a reference image.
- Fully functional Flask web interface with styled UI.
- Saves uploaded images in a local folder (`static/upload/`) for later review.

---

## 🛠️ Tech Stack

- **Language:** Python 3.10+
- **Framework:** Flask (for web backend)
- **Deep Learning:** TensorFlow 2.12.0, Keras
- **Libraries:** OpenCV, NumPy, Pandas, Matplotlib
- **Frontend:** HTML, CSS, Bootstrap (optional)
- **Model:** CNN trained on PlantVillage dataset
- **Deployment:** Localhost or can be deployed on Render, Heroku, etc.

---

## 📂 Project Structure

crop-disease-app/ ├── static/ │ └── upload/ # Folder where uploaded images are saved ├── templates/ │ └── index.html # Main UI template ├── class_indices.json # Class label mappings ├── disease_info.json # Descriptions, precautions, links ├── crop_disease_model.keras # Trained CNN model ├── app.py # Flask application └── README.md

---

## 🧠 Model Info

The CNN model was trained using the PlantVillage dataset, consisting of 38 labeled crop diseases and healthy leaves. The model uses binary or categorical classification based on user configuration. It includes preprocessing, data augmentation, and dropout layers to avoid overfitting.

---

## 📦 How to Run the Project

Follow these simple steps to run the app locally:

1. **Clone the Repository**
   ```bash
  
https://github.com/Durwang2002/-Customer-Segmentation-Using-K-Means-Clustering.git
