# Road Anomaly Classifier

## Project Description
This project is a computer vision system for detecting road hazards using machine learning.

The classifier distinguishes between:
- Potholes
- Road debris / road objects

## Objective
The goal of the project is to help autonomous and smart mobility systems detect dangerous road conditions automatically.

## Pipeline
1. Data collection
2. Image preprocessing
3. HOG feature extraction
4. SVM classification
5. Model evaluation

## Technologies Used
- Python
- OpenCV
- scikit-image
- scikit-learn
- Google Colab

## Input
Road surface images resized to 128×128 pixels.

## Output
Predicted class:
- Pothole
- Debris

## Model
The project uses:
- HOG (Histogram of Oriented Gradients)
- SVM (Support Vector Machine)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Conclusion
This milestone presents a baseline classifier for road hazard detection. Future improvements can include larger datasets and deep learning models.