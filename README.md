# AI-Based Signature Recognition System

This project implements an AI-based Signature Recognition System to distinguish between genuine and forged signatures using image processing and machine learning techniques. The system leverages preprocessed signature images to train classification models and evaluate their accuracy, making it applicable for security, banking, and document verification purposes.

## Project Overview

Signature recognition is a widely used biometric technique for verifying an individual's identity. This project focuses on offline (static) signature recognition, where the user writes a signature on paper, and it is then scanned and analyzed as an image. The model extracts relevant features and classifies the signature as either genuine or forged.

The complete pipeline includes:

- Data preprocessing
- Feature extraction
- Machine learning model training and testing
- Evaluation with accuracy scores and confusion matrix

## Objectives

- Design and implement an AI-based signature verification system
- Develop a classification model to differentiate genuine and forged signatures
- Evaluate the model on performance metrics like accuracy and precision
- Explore potential applications in biometric verification systems

## Technologies Used

- **Language**: Python
- **Libraries**:
  - OpenCV
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
- **Tools**: Visual Studio Code, Jupyter Notebook

## Folder Structure
signature_recognition/
├── dataset/
│ ├── genuine/
│ └── forged/
├── preprocessing.py
├── model.py
├── evaluation.py
├── results/
└── README.md
## Installation

Install the required Python packages before running the project:

```bash
pip install numpy pandas matplotlib scikit-learn opencv-python

How to Run
Prepare your dataset with subfolders: /genuine and /forged.
Run preprocessing.py to extract features and save them as training data.
Run model.py to train the classifier.
Use evaluation.py to generate accuracy scores and confusion matrix.

