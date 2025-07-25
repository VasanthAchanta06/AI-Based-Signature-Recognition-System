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

## Key Features:
Offline signature verification using image preprocessing and ML.
Feature extraction with OpenCV; classification using Scikit-learn.
Evaluated with accuracy, precision, recall, and F1-score.
Modular design; scalable for CNN and dynamic input integration.
Applicable in banking, legal, and biometric systems.

## Evaluation Metrics:
Accuracy
Precision
Recall
Confusion Matrix

## Results:
The trained model achieved high accuracy in differentiating between genuine and forged signatures. The evaluation results show promising application in real-world authentication scenarios.

## Applications:
Banking and financial document authentication
Legal document verification
Biometric systems for secure access

## Future Work
Integration with online signature recognition (dynamic input)
Application of CNN-based models for enhanced accuracy
Development of a web-based interface using Flask or Streamlit

Author
Vasanth Achanta





