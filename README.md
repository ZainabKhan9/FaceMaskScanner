# FaceMaskScanner
An AI-powered system for detecting face masks using deep learning. This project supports both real-time webcam-based detection and image upload-based mask classification using a MobileNetV2 model. Built with TensorFlow, OpenCV, and an intuitive UI for user interaction.
FaceMaskScanner is an AI-based application designed to detect whether a person is wearing a face mask or not. It supports both real-time detection using a webcam and image upload-based detection through a simple user interface.

The system is built using the MobileNetV2 model, a lightweight and efficient deep learning architecture suitable for real-time applications. The project uses TensorFlow and OpenCV for model development and image processing, and Gradio is used for building an interactive UI.

Features:

Real-time face mask detection using webcam

Image upload and classification with prediction result

Lightweight and fast MobileNetV2 model

User-friendly interface using Gradio

Easy to extend with custom data

Folder Structure:

model/

face_mask_model.h5 – Trained model file

scripts/

face_mask_detection.py – Code for model training and evaluation

live_detection.py – Script for real-time webcam detection

notebooks/

train_and_eval.ipynb – Notebook for training the model

ui_upload_predict.ipynb – Notebook interface for image upload and prediction

Other files:

requirements.txt – Python dependencies

README.md – Project overview

LICENSE – Project license (MIT)

How to Run:

Clone the repository
git clone https://github.com/ZainabKhan9/FaceMaskScanner.git

cd FaceMaskScanner

Install dependencies
pip install -r requirements.txt

Run real-time webcam detection
python scripts/live_detection.py

Run image upload UI (in Jupyter Notebook/ google colab)
Open notebook/ui_upload_predict.ipynb and run all cells

Collaborators:
Zainab Khan
Aashray Kusumbe
