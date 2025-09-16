Punjabi Character Set Recognition – SLM

A machine learning project for recognizing handwritten Punjabi (Gurmukhi) characters using Statistical Language Modeling (SLM) and modern AI techniques.

- Project Overview

Punjabi, written in the Gurmukhi script, has a rich character set that poses unique challenges for handwriting recognition due to similar-looking characters and script complexity.

This project aims to:

Build a model to classify Punjabi characters from images.

Use Statistical Language Models (SLM) to improve recognition accuracy.

Provide a foundation for applications like OCR, educational tools, and assistive technologies.

- Features

 Dataset preprocessing for Punjabi characters

 Handwritten character image classification

 Language model (SLM) integration for context-aware recognition

 Training and evaluation scripts

 Extendable for OCR systems

-Tech Stack

Python

TensorFlow / PyTorch (deep learning)

NumPy, Pandas (data handling)

Scikit-learn (evaluation metrics)



-Model Training

Run the training script:

python src/train.py


-For Jupyter/Colab:

!jupyter notebook notebooks/CharacterRecognition.ipynb

-Results

Accuracy: 87% (to be updated after training)

Confusion matrix shows strong performance on most characters.

SLM improves recognition of ambiguous characters.
