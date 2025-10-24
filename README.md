# Vision-Based Location Recognition for Visually Impaired People

## Project Overview
This project presents a vision-based location recognition system designed to assist visually impaired individuals by identifying and localizing specific places within an indoor environment using computer vision techniques. The system collects visual data via a camera, extracts distinctive features, and matches these with known environments to identify location. The recognized location is then announced through an audio interface, enabling safe and independent indoor navigation.

## Key Features
- Utilizes Fast Retina Keypoint (FREAK) descriptor and Features from Accelerated Segment Test (FAST) algorithm for fast and reliable feature extraction.
- Implements Support Vector Machine (SVM) and clustering methods for accurate location classification.
- Designed for real-world use cases, tested within campus environments.
- Provides real-time voice feedback for smooth user interaction.
- Significantly improves automated location awareness for visually impaired users.

## Technologies and Tools
- Python, OpenCV, NumPy, Scikit-learn
- FAST and FREAK feature extractors
- Machine learning algorithms (SVM)
- Jupyter Notebooks for experimentation and documentation

## Dataset
The dataset consists of a diverse set of images (>10GB) captured at various indoor environments. Due to GitHub storage limits, dataset download links and preprocessing details are included in the `dataset.md` file.

## Research Paper
Detailed explanation and analysis are published in the paper:
**Vision-Based Location Recognition for Visually Impaired People**  
Authors: Jyoti Madake, Akash Shekhavat, Madhuri Shelke, Shripad Bhatlawande  
(Available in the https://ieeexplore.ieee.org/document/10560251

## Usage
1. Clone the repository and install dependencies:
