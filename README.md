# EEG Parkinson's Disease Detection

![EEG PD Detection](https://img.shields.io/badge/Parkinson's%20Disease-Detection-brightgreen)

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)

Early detection of Parkinson's Disease is crucial for effective treatment and management. This repository hosts a unique solution that employs Electroencephalography (EEG) data to detect the onset of Parkinson's Disease at an early stage. Our approach leverages various EEG signal processing techniques and artificial neural networks for accurate detection.

## Project Overview

Electroencephalography is a non-invasive method that records electrical activity in the brain. Neuronal dysfunction or neuronal death is often associated with behavioral aberrations, leading to abnormal brain electrical activity. The primary goal of this project is to extract features from EEG data and analyze them to detect Parkinson's Disease at an early stage.

## Features

Our approach utilizes the following markers and techniques for early Parkinson's Disease detection:

- **Welch's Power Spectral Density:** Examining the power spectral density of EEG signals.

- **Hjorth Parameters:** Analyzing Hjorth complexity, activity, and mobility.

- **Hurst Exponent:** Calculating the Hurst exponent for EEG data.

- **Information Factors:** Extracting information factors.

- **FastICA:** Using Fast Independent Component Analysis for data preprocessing.

- **Artificial Neural Network:** Building a classifier with ReLU and Sigmoidal Activation Functions.

## Project Structure

This repository contains two essential notebooks:

1\. **EEG Data Processing.ipynb**

   - Reads and processes EEG data.

   - Performs FastICA for preprocessing.

   - Calculates power spectral density and Hjorth parameters.

   - Computes complexity, activity, and mobility.

   - Extracts information factors.

2\. **EEG PD Classifier.ipynb**

   - Prepares data for training.

   - Scales data using Min-Max scaling.

   - Builds and trains an artificial neural network.

   - Evaluates the model's performance and generates a confusion matrix.

## Results

Our model achieves an impressive accuracy of 93.3% on the training data and 88.17% on the test data, showcasing its effectiveness in early Parkinson's Disease detection.

## Getting Started

1\. Clone the repository:

   ```
   git clone https://github.com/therealnaveenkamal/parkinsons_detector.git
   ```

2\. Open the notebooks in Jupyter or your preferred Python environment and run them to process EEG data and build the Parkinson's Disease detection model.

## Acknowledgments

- The project leverages the power of EEG data and machine learning to make early Parkinson's Disease detection accessible.

- The code in this repository is for educational and research purposes and should be used responsibly.

If you find this project interesting or have suggestions for improvements, feel free to contribute or create issues. Early detection of Parkinson's Disease can have a significant impact on the quality of life for affected individuals, and we hope this project contributes to this noble cause.

Give it a star if you like it! ⭐

**Disclaimer:** This project is not a replacement for professional medical advice, diagnosis, or treatment. Always consult a healthcare professional for medical concerns.
