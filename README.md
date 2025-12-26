🧠 Brain Tumour Detection and 3D Visualization

This project aims to detect brain tumours from MRI images using deep learning and provide an interactive 3D visualization of the human brain through a web-based interface.

The system integrates a trained deep learning model with a Flask web application, allowing users to upload MRI images, perform tumour detection, and visualize anatomical regions using a 3D brain model.

🎯 Objectives

Detect the presence of brain tumours from MRI scans

Classify tumour types using a trained deep learning model

Provide an intuitive web interface for interaction

Visualize brain anatomy in 3D for better understanding

Serve as an academic major project under guided development

✨ Features

📤 Upload MRI images via web interface

🤖 Tumour detection using a YOLO-based deep learning model

📊 Result display with tumour / no-tumour classification

🧠 Interactive 3D brain visualization (.glb model)

🌐 Flask-based backend and HTML frontend

🛠️ Technology Stack

Python

Flask

Ultralytics YOLO

OpenCV

NumPy

HTML / CSS / JavaScript

Three.js (for 3D visualization)

📂 Project Structure
Brain-Tumour-Detection-and-3D-Visualization/
│
├── components/                # Helper / experimental components
│
├── models/                    # Trained deep learning models
│   ├── best.pt
│   └── fibonacci_model.h5
│
├── static/
│   ├── brain.glb              # 3D brain model
│   └── uploads/               # Uploaded MRI images (runtime, ignored)
│
├── templates/                 # HTML templates
│   ├── index.html
│   ├── index2.html
│   ├── index3.html
│   ├── tumor_dashboard.html
│   ├── visualize.html
│   └── no_tumor.html
│
├── main2.py                   # Main Flask application (entry point)
├── main3.py                   # Extended / alternate logic
├── combine.py                 # Helper functions
├── fibonacciNet.py            # Additional model logic
├── ai_bot.py                  # Experimental AI assistant logic
├── ai_bot.go                  # Experimental Go-based component
├── explode_effect.html        # Standalone visualization experiment
│
├── requirements.txt
├── README.md
└── .gitignore

🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/shantanumohod23/Brain-Tumour-Detection-and-3D-Visualization.git
cd Brain-Tumour-Detection-and-3D-Visualization

2️⃣ Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Run the application
python main2.py

5️⃣ Open in browser
http://127.0.0.1:5000

📦 Model & Asset Files

The following large files are included in the repository but are excluded from Git versioning and uploaded manually to avoid repository size and dependency issues:

models/best.pt

models/fibonacci_model.h5

static/brain.glb

These files are required for full functionality.

⚠️ Important Notes

This project currently focuses on model inference and visualization.

Model training was performed earlier using a brain MRI dataset.

Uploaded MRI images are stored temporarily and are not tracked by Git.

API keys and sensitive configurations are managed via environment variables.

🎓 Academic Context

This project is developed as part of an engineering major project, demonstrating the application of:

Machine Learning & Deep Learning

Computer Vision

Web Application Development

3D Visualization

The project will be further enhanced in future stages under academic guidance.

👤 Author

Shantanu Mohod
Engineering Student
Major Project – Brain Tumour Detection & Visualization