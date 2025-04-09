# fruit-quality-detection
This project uses Deep Learning and Flask to detect fruit type (Apple, Banana, Orange), classify it as Fresh or Not Fresh, and show freshness percentage. It offers a web interface for real-time image-based fruit quality analysis using pretrained models.
cat << 'EOF' > README.md
# 🍎 Fruit Quality Detection using Deep Learning and Flask

This project is a Fruit Quality Detection System built using Deep Learning and Flask. It analyzes images of fruits to:
- ✅ Detect the type of fruit (Apple, Banana, Orange)
- ✅ Classify whether the fruit is Fresh or Not Fresh
- ✅ Provide a percentage score showing how fresh or rotten the fruit is

The system is trained on a custom dataset with multiple fruit categories and uses pretrained deep learning models for accurate predictions. It provides an intuitive web interface where users can upload fruit images and get real-time results.

---

## 📌 Features

- 🔍 Predicts the **type of fruit**
- ✅ Classifies fruit as **Fresh** or **Not Fresh**
- 📊 Shows **freshness percentage**
- 🧠 Uses pretrained models (InceptionResNetV2, MobileNetV2)
- 🌐 User-friendly Flask web app

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- Flask (Web Framework)
- HTML, CSS, JavaScript

---

## 📂 Dataset

- Custom dataset of fruit images
- Categories: Apple, Banana, Orange
- Labels: Fresh, Not Fresh

Folder structure:
dataset/ ├── train/ │ ├── Apple/ │ │ ├── Fresh/ │ │ └── Not_Fresh/ │ ├── Banana/ │ └── Orange/

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

python app.py

