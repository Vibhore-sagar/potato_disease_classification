# Potato Disease Classification 

This project aims to classify potato leaf diseases using a machine learning model, making it easier for farmers and agricultural experts to diagnose plant health. It features a complete pipeline, including a TensorFlow-based model, FastAPI backend, and a ReactJS-powered frontend for user interaction.

# Table of Contents
1. Overview
2. Features
3. Tech Stack
4. Setup Instructions
5. Usage
6. Acknowledgements

# Overview
This project aims to solve the issue of potato plant diseases by leveraging deep learning. Using a convolutional neural network (CNN) built with TensorFlow, the model classifies images of potato leaves into different categories (e.g., healthy, late blight, early blight). The solution includes:

+ Backend using FastAPI to handle predictions.
+ Frontend built with ReactJS to allow users to upload leaf images for classification.

# Features
+ Machine Learning Model: A TensorFlow CNN trained on potato leaf datasets.
+ FastAPI Backend: Serves predictions in real-time through an API.
+ ReactJS Frontend: A simple, interactive web interface for users to upload images and view predictions.

# Tech Stack
+ Python: Core programming language.
+ TensorFlow: Model development and training.
+ FastAPI: Backend for serving predictions via APIs.
+ ReactJS: Frontend for user interaction.

# Setup Instructions
## Prerequisites
+ Python 3.x
+ Node.js and npm
+ TensorFlow
+ FastAPI
+ ReactJS

## 1. Clone the Repository
```
git clone https://github.com/your-username/potato-disease-classification.git
cd potato-disease-classification
```
## 2. Backend Setup (FastAPI)
1. Navigate to the ```backend/``` folder
2. Install dependencies:
```
 pip install -r requirements.txt
```
3. Run the FastAPI server:
```
uvicorn main:app --reload
```
## 3. Frontend Setup (ReactJS)
1. Navigate to the ```frontend/``` folder.
2. Install dependencies:
```
npm install
```
3. Run the React server:
```
npm start
```
# Usage
1. Launch both the FastAPI backend and ReactJS frontend servers.
2. Open the ReactJS web interface in your browser at ```http://localhost:3000```.
3. Upload an image of a potato leaf using the provided interface.
4. The backend will process the image and return a prediction, displayed on the frontend

# Acknowledgements 
+ TensorFlow for the machine learning framework.
+ FastAPI for the backend development.
+ ReactJS for the frontend interface

