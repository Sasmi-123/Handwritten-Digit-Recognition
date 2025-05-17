# Handwritten Digit Recognition with Deep Learning

This project builds a deep learning model using TensorFlow/Keras to recognize handwritten digits from the MNIST dataset. It also uses a Gradio interface to allow users to draw digits live in the browser and get predictions.

## Features

- CNN model trained on MNIST
- Test predictions using an unlabeled CSV dataset
- Live digit drawing with Gradio

## How to Run

```bash
pip install tensorflow pandas matplotlib gradio
python generate_unlabeled_csv.py
python digit_recognition.py
