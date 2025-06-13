# 🔍 Transistor Anomaly Detection App

An AI-powered web app for automated quality inspection of transistor components and circuit boards using computer vision.

---

## 🚀 Project Overview

The **Transistor Anomaly Detection App** is built to help engineers and quality inspectors quickly detect defects or irregularities in transistor circuits. Leveraging deep learning models trained with Google Teachable Machine, this app simplifies manual inspection with a fast, scalable, and accurate AI solution.

---

## 🧠 Model Building

- Built using **Google Teachable Machine**
- Trained for **binary classification**:
  - ✅ Good (Normal)
  - ⚠️ Anomaly (Defective/Damaged)
- Exported as `.h5` Keras model and integrated into a Streamlit app

---

## 📂 Dataset Source

- Dataset created by collecting transistor and circuit board images from Mvtec Datasets.
- Classes:
  - Good Transistors
  - Defective Transistors (burn marks, bent pins, cracks)
- Used for training and validation via Teachable Machine

---

## 💡 App Features

- 📁 Upload or 📷 capture circuit images
- 🧠 On-device AI model prediction
- 🔍 Predicts image status as **Good** or **Anomaly**
- ✅ Real-time, user-friendly interface built with Streamlit

---

## 🛠️ Technologies Used

- Python
- Streamlit
- TensorFlow / Keras
- Google Teachable Machine
- Computer Vision & Deep Learning
- Git & GitHub

---

## 📁 Project Structure
Transistor-Anomaly-Detection_App/
│
├── .devcontainer/
│ └── devcontainer.json
│
├── .streamlit/
│ └── config.toml
│
├── images/
│ ├── AI_Project_Cycle.jpg
│ ├── model_inference_pipeline.png
│ ├── model_train_pipeline.png
│ ├── overview_dataset.jpg
│ └── transistor2.png
│
├── App.py # Main Streamlit application
├── keras_model.h5 # Trained classification model
├── labels.txt # Class labels
├── packages.txt # Required packages
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── .gitignore

---

## ✅ How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/darshan1654/Transistor-Anomaly-Detection_App.git
   cd Transistor-Anomaly-Detection_App

2. Install dependencies:
   pip install -r requirements.txt

3. Run the App:
   streamlit run App.py

---

## 📌 Conclusion
This app showcases how deep learning and computer vision can automate visual inspection in electronics manufacturing. It serves as a foundation for deploying real-world quality control tools with AI.

---

## 🙌 Acknowledgements
- Google Teachable Machine
- Streamlit Community
- OpenAI for guidance


