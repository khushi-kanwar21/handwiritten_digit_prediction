This project demonstrates a handwritten digit recognition system built with TensorFlow and deployed using Gradio for an interactive web interface.

Overview
The system takes a user’s hand-drawn digit as input (via a sketchpad) and predicts the digit (0-9) using a trained neural network model based on the MNIST dataset. The model processes the input image, converts it to grayscale, resizes it to 28x28 pixels, normalizes the pixel values, and outputs the predicted digit.

Features
Interactive drawing pad for digit input

Preprocessing of hand-drawn images for model compatibility

Deep learning model trained on MNIST dataset

Easy-to-use web interface powered by Gradio

Real-time digit prediction with high accuracy

Technologies Used
Python

TensorFlow / Keras

NumPy

Gradio (for web interface)

MNIST Dataset for training

How to Use
Run the Python script to launch the Gradio interface.

Draw a digit (0-9) on the sketchpad.

Get instant predictions from the trained model.
