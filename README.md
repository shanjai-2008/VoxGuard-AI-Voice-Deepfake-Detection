# VoxGuard – AI Voice Deepfake Detection

VoxGuard is an AI-based audio classification project designed to distinguish genuine human speech from synthetic or manipulated voice recordings.

## Overview
The project uses audio preprocessing, spectrogram feature extraction, and a Convolutional Neural Network (CNN) to classify audio samples.

## Technologies Used
- Python
- PyTorch
- CNN
- STFT (Short-Time Fourier Transform)
- SciPy
- FastAPI

## Key Features
- Audio preprocessing and normalization
- Mono conversion and resampling to 16 kHz
- Fixed-length audio cropping and padding
- Spectrogram-based feature extraction
- CNN-based audio classification
- FastAPI integration
- Audio upload and microphone inference support

## Model Evaluation
Evaluated using the ASVspoof 2019 LA development dataset.

- Accuracy: 86.74%
- ROC-AUC: 99.22%

*Results represent the project's reported evaluation and not real-world guarantees.*

## Purpose
Explore the use of deep learning techniques for detecting AI-generated and manipulated audio and investigate audio-based authenticity analysis.

## Project Status
Academic project.

