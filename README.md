# 🧠 Brain Tumour Detection and 3D Visualization

This project focuses on detecting brain tumours from MRI images using deep learning
and visualizing the brain in 3D through a web-based interface.

The system integrates a trained deep learning model with a Flask application,
allowing users to upload MRI images, perform tumour detection, and visualize
anatomical regions using a 3D brain model.

---

## 🎯 Objectives

- Detect brain tumours from MRI scans
- Classify tumour presence using a deep learning model
- Provide a web-based interface for interaction
- Visualize brain anatomy in 3D
- Develop the project in academic stages under guidance

---

## ✨ Features

- Upload MRI images
- Tumour detection using YOLO-based model
- Tumour / No-tumour result display
- Interactive 3D brain visualization
- Flask backend with HTML frontend

---

## 🛠️ Technology Stack

- Python
- Flask
- Ultralytics YOLO
- OpenCV
- NumPy
- HTML, CSS, JavaScript
- Three.js (for 3D visualization)

---

## 📂 Project Structure

Brain-Tumour-Detection-and-3D-Visualization/
│
├── components/
├── models/
│ ├── best.pt
│ └── fibonacci_model.h5
│
├── static/
│ ├── brain.glb
│ └── uploads/
│
├── templates/
│ ├── index.html
│ ├── index2.html
│ ├── index3.html
│ ├── tumor_dashboard.html
│ ├── visualize.html
│ └── no_tumor.html
│
├── main2.py
├── main3.py
├── combine.py
├── fibonacciNet.py
├── ai_bot.py
├── ai_bot.go
├── explode_effect.html
│
├── requirements.txt
├── README.md
└── .gitignore

## 🚀 How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/shantanumohod23/Brain-Tumour-Detection-and-3D-Visualization.git
cd Brain-Tumour-Detection-and-3D-Visualization
2. Create and activate virtual environment
bash
Copy code
python -m venv venv
venv\Scripts\activate
3. Install dependencies
bash
Copy code
pip install -r requirements.txt
4. Run the application
bash
Copy code
python main2.py
5. Open in browser
cpp
Copy code
http://127.0.0.1:5000
📦 Model and Asset Files
The following files are uploaded manually and excluded from Git versioning
to avoid repository size and dependency issues:

models/best.pt

models/fibonacci_model.h5

static/brain.glb

These files are required for full functionality.

⚠️ Notes
This project currently focuses on inference and visualization.

Model training was performed earlier using a brain MRI dataset.

Uploaded images are stored temporarily and ignored by Git.

Sensitive keys are managed using environment variables.

🎓 Academic Context
This project is developed as part of an engineering major project
demonstrating the application of:

Machine Learning

Computer Vision

Web Development

3D Visualization

Future stages will enhance accuracy, UI, and explainability.

👤 Author
Shantanu Mohod
Engineering Student
Brain Tumour Detection and 3D Visualization Project
