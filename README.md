# Video Frame Prediction using Autoencoder

## Overview
This project presents an AI-driven solution for predicting future frames in video sequences using autoencoder neural networks. 
Traditional methods often struggle with issues like quality degradation and high computational costs. 
Our approach employs autoencoder networks to effectively capture complex temporal dependencies and produce accurate frame predictions.

## Features
- **YouTube Video Downloading**: Integration with YouTube API for video retrieval.
- **Frame Extraction**: Extraction of frames from videos using OpenCV.
- **Autoencoder Model Construction**: Implementation of a convolutional autoencoder using TensorFlow/Keras.
- **Training and Optimization**: Optimization of model parameters using Adam optimizer and mean squared error loss.
- **Frame Prediction**: Generation of future frame predictions based on trained models.
- **Evaluation Metrics**: Quantitative evaluation using mean squared error and qualitative assessment through visual comparisons.

## Usage
1.  Download `Convolutional_AutoEncoder.ipynb`.
2.  Upload and Run the file on Colab to download videos, extract frames, train models, and generate predictions.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- OpenCV
- Matplotlib
