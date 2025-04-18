# 🌿 Plant Disease Detection using CNN in Google Colab

This project demonstrates how to build and run a simple Convolutional Neural Network (CNN) for plant disease detection using the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease) in **Google Colab**. It walks through every step, from downloading the dataset with Kaggle API to training and testing a model.

---

## 🚀 Project Highlights

- 📦 Dataset: PlantVillage (Healthy and diseased leaves)
- 🧠 Model: CNN with TensorFlow/Keras
- 🧪 Task: Multi-class image classification
- 🖥️ Platform: Google Colab

---

## 📁 Files Included

- `plant_disease_colab_guide.py` — Main Python code for running the full workflow in Colab.
- `README.md` — Instructions and project overview.

---

## 🧭 How to Run This Project

### 1. Upload to Google Colab

Open [Google Colab](https://colab.research.google.com/), create a new notebook, and copy-paste the code from `plant_disease_colab_guide.py`.

### 2. Set up Kaggle

1. Go to your [Kaggle Account](https://www.kaggle.com/account)
2. Scroll to API → Click **Create New API Token**
3. Download `kaggle.json`
4. Upload it inside Colab when prompted

### 3. Execute Steps

- Download and unzip the dataset using Kaggle API
- Load and preprocess images using `ImageDataGenerator`
- Build and train the CNN model
- Visualize training accuracy
- Predict any uploaded leaf image

---

## 📊 Output

- Training and validation accuracy graph
- Predicted class of uploaded custom image

---

## 🙌 Acknowledgements

- Dataset by Emma Rex on Kaggle
- TensorFlow and Keras for model training

---

## 📌 License

This project is free to use for educational purposes.
