# Face Shape Detection & Hairstyle Recommendation Using Deep Learning

A deep learning-based web application that detects a person’s **face shape** from an uploaded image and provides **personalized hairstyle recommendations** based on the detected shape.

### 🔍 Key Features

* Upload a photo and automatically detect the face shape.
* Classifies face shapes such as **Oval, Heart, Square, Long, and Round**.
* Detects and displays **facial landmarks** using Dlib.
* Provides personalized hairstyle recommendations with names, descriptions, and reference images.
* Interactive and user-friendly web interface.

### 🌍 Real-World Applications

* **Virtual Makeovers:** Helps users explore hairstyles before visiting a salon.
* **Personalized Styling:** Can recommend suitable glasses, accessories, and hairstyles based on face shape.
* **Beauty & E-commerce Platforms:** Can be integrated into personalized styling and recommendation systems.
* **Content Creation:** Useful for fashion, beauty, and styling platforms.

### 💻 Technology Stack

**Backend & AI**

* Python
* Flask
* TensorFlow & Keras
* VGG16 with Transfer Learning
* Dlib
* OpenCV
* Pillow

**Frontend**

* React.js
* React Router
* Axios
* CSS

### 🚀 How to Run the Project

**1. Start the Backend**

Open the `backend` folder in VS Code and create a Python virtual environment:

```bash
python -m venv venv
```

Activate the environment and install the required dependencies:

```bash
pip install -r requirements.txt
```

Run the Flask server:

```bash
python app.py
```

The backend will usually run at:

`http://localhost:5000`

**2. Start the Frontend**

Open a new terminal and navigate to the `frontend` folder:

```bash
npm install
npm start
```

The application will usually open at:

`http://localhost:3000`

Upload a photo and let the system detect the face shape and recommend suitable hairstyles.

### 🎯 Project Objective

The main objective of this project is to combine **Deep Learning, Computer Vision, and Web Development** to create an intelligent and practical hairstyle recommendation system that provides users with personalized styling suggestions based on their facial features.

