# 🧠 Brain Tumour Detection and 3D Visualization

This project focuses on detecting brain tumours from MRI images using deep learning
and visualizing the human brain in 3D through a web-based interface.

The system integrates a trained deep learning model with a Flask web application,
allowing users to upload MRI images, perform tumour detection, and visualize
anatomical regions using an interactive 3D brain model.

---

## 🎯 Objectives

- Detect the presence of brain tumours from MRI scans
- Classify tumour presence using a deep learning model
- Provide a web-based interface for interaction
- Visualize brain anatomy in 3D
- Develop the project in academic stages under guidance

---

## ✨ Features

- Upload MRI images through a web interface
- Tumour detection using a YOLO-based deep learning model
- Tumour / No-Tumour result display
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
```
Brain-Tumour-Detection-and-3D-Visualization/
|
|-- components/
|
|-- models/
| |-- best.pt
| -- fibonacci_model.h5 | |-- static/ | |-- brain.glb | -- uploads/
|
|-- templates/
| |-- index.html
| |-- index2.html
| |-- index3.html
| |-- tumor_dashboard.html
| |-- visualize.html
| -- no_tumor.html | |-- main2.py |-- main3.py |-- combine.py |-- fibonacciNet.py |-- ai_bot.py |-- ai_bot.go |-- explode_effect.html | |-- requirements.txt |-- README.md -- .gitignore
```
## 🚀 How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/shantanumohod23/Brain-Tumour-Detection-and-3D-Visualization.git
   cd Brain-Tumour-Detection-and-3D-Visualization

3. Create and activate a virtual environment
   ```bash
   python -m venv venv
   venv\Scripts\activate

5. Install dependencies
   ```bash
   pip install -r requirements.txt

7. Run the application
   ```bash
   python main2.py

9. Open in browser
    ```bash
   http://127.0.0.1:5000
    
📦 Model and Asset Files
The following large files are uploaded manually and excluded from Git versioning
to avoid repository size and dependency issues:
```bash
models/best.pt

models/fibonacci_model.h5

static/brain.glb

These files are required for full functionality of the project.
```
⚠️ Important Notes
This project currently focuses on model inference and visualization

Model training was performed earlier using a brain MRI dataset

Uploaded MRI images are stored temporarily and ignored by Git

API keys and sensitive configurations are managed using environment variables

🎓 Academic Context
This project is developed as part of an Engineering Major Project, demonstrating the application of:

Machine Learning & Deep Learning

Computer Vision

Web Application Development

3D Visualization

The project will be further enhanced in future stages under academic guidance.

👤 Author
Shantanu Mohod
Engineering Student
Major Project – Brain Tumour Detection and 3D Visualization
