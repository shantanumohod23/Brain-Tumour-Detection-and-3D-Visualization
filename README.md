BRAIN TUMOUR DETECTION AND 3D VISUALIZATION


PROJECT OVERVIEW
----------------
This project focuses on detecting brain tumours from MRI images using deep learning
and visualizing the human brain in 3D through a web-based interface.

The system integrates a trained deep learning model with a Flask application,
allowing users to upload MRI images, perform tumour detection, and visualize
anatomical regions using an interactive 3D brain model.


OBJECTIVES
----------
• Detect brain tumours from MRI scans
• Classify tumour presence using a deep learning model
• Provide a web-based interface for interaction
• Visualize brain anatomy in 3D
• Develop the project in academic stages under guidance


KEY FEATURES
------------
• MRI image upload functionality
• Tumour detection using YOLO-based deep learning model
• Tumour / No-Tumour classification output
• Interactive 3D brain visualization
• Flask-based backend with HTML frontend


TECHNOLOGY STACK
----------------
• Python
• Flask
• Ultralytics YOLO
• OpenCV
• NumPy
• HTML, CSS, JavaScript
• Three.js (for 3D visualization)


PROJECT STRUCTURE
-----------------
Brain-Tumour-Detection-and-3D-Visualization/

|-- components/
|
|-- models/
|   |-- best.pt
|   |-- fibonacci_model.h5
|
|-- static/
|   |-- brain.glb
|   |-- uploads/
|
|-- templates/
|   |-- index.html
|   |-- index2.html
|   |-- index3.html
|   |-- tumor_dashboard.html
|   |-- visualize.html
|   |-- no_tumor.html
|
|-- main2.py
|-- main3.py
|-- combine.py
|-- fibonacciNet.py
|-- ai_bot.py
|-- ai_bot.go
|-- explode_effect.html
|
|-- requirements.txt
|-- README.md
|-- .gitignore


HOW TO RUN THE PROJECT
---------------------
1. Clone the repository
   git clone https://github.com/shantanumohod23/Brain-Tumour-Detection-and-3D-Visualization.git

2. Create and activate virtual environment
   python -m venv venv
   venv\Scripts\activate

3. Install dependencies
   pip install -r requirements.txt

4. Run the application
   python main2.py

5. Open in browser
   http://127.0.0.1:5000


MODEL AND ASSET FILES
--------------------
The following large files are included in the project but excluded from Git
versioning and uploaded manually to avoid repository size and dependency issues:

• models/best.pt
• models/fibonacci_model.h5
• static/brain.glb

These files are required for full functionality.


IMPORTANT NOTES
---------------
• The project currently focuses on model inference and visualization
• Model training was performed earlier using a brain MRI dataset
• Uploaded images are stored temporarily and ignored by Git
• Sensitive API keys are managed using environment variables


ACADEMIC CONTEXT
----------------
This project is developed as part of an Engineering Major Project and demonstrates
the application of:

• Machine Learning
• Computer Vision
• Web Development
• 3D Visualization

Future stages will enhance model accuracy, user interface, and explainability.


AUTHOR
------
Shantanu Mohod
Engineering Student
Brain Tumour Detection and 3D Visualization Project
