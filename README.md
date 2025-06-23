# GrainPalette – A Deep Learning Odyssey in Rice Type Classification

GrainPalette is a deep learning-powered web application that classifies rice grain types using transfer learning. It allows users to upload an image and receive real-time predictions through a clean and modern web interface built with Flask.

---

## 🖼️ Project Preview

<p align="center">
  <img src="static/images/rice_bg.jpg" alt="Rice background" width="80%" />
  <br><br>
  <img src="static/images/app_screenshot.png" alt="App screenshot" width="80%" />
</p>

---

## 🚀 Live Demo

🧪 Currently runs locally  
🌐 Deployment on Render/Hugging Face coming soon!

---

## 📌 Features

- 🧠 Built with **Transfer Learning** using Keras/TensorFlow
- 🌾 Classifies rice into 5 types:
  - Basmati
  - Jasmine
  - Arborio
  - Brown
  - White
- 🖼️ Upload an image and get predictions instantly
- 📊 Shows prediction with confidence score
- 🧠 Model code available in `model.ipynb`
- 🎨 Modern UI with navbar, background, and animations

---

## 🗂 Project Structure

GrainPalette/
├── app.py # Flask backend
├── rice_model.h5 # Trained rice classification model
├── model.ipynb # Jupyter notebook for model training
├── templates/ # HTML files
│ ├── index.html
│ ├── predict.html
│ ├── details.html
│ └── contact.html
├── static/ # CSS, images, styling
│ ├── style.css
│ └── images/
│ ├── rice_bg.jpg
│ └── app_screenshot.png
├── uploads/ # Uploaded files (auto-created)
└── README.md


---

## ⚙️ Installation & Run Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/GrainPalette.git
cd GrainPalette

conda create -n grainpalette python=3.9
conda activate grainpalette


python app.py

