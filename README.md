# Automated Image Culling System

## Overview
The **Automated Image Culling System** is a Python-based application designed to evaluate and rank images based on their quality. By analyzing various parameters such as sharpness, contrast, resolution, facial expressions, colorfulness, brightness, and noise levels, the system filters out low-quality images and organizes them into a discard folder.

## Features
- **Image Quality Analysis**: Evaluates images using advanced metrics like sharpness, contrast, and facial expressions.
- **Feature Extraction**: Uses a pre-trained VGG16 model to extract image features.
- **Black-and-White Detection**: Identifies and adjusts scoring for black-and-white images.
- **Dynamic Scoring System**: Normalizes and scales various quality metrics to calculate an overall quality score.
- **Automated Discarding**: Moves low-quality images to a discard folder for review.

## Technology Stack
- **Python**: Core programming language.
- **OpenCV**: For image processing tasks.
- **TensorFlow/Keras**: Pre-trained VGG16 model for feature extraction.
- **FER**: Facial expression recognition library.
- **Skimage**: For calculating sharpness and contrast.
- **NumPy**: For efficient numerical computations.
- **Scikit-learn**: For standardizing feature data.

## Folder Structure
- **Input Folder**: Contains the images to be analyzed.
- **Discard Folder**: Stores images deemed low-quality based on the scoring threshold.



