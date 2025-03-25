# Stress Detection System Using Image Processing and Machine Learning

## Introduction

Stress significantly affects mental health, causing socio-economic problems, reduced clarity in work, deteriorating relationships, depression, and severe cases may lead to suicide. This project addresses the critical need for automated stress detection to facilitate timely counseling and preventive measures.

## Problem Definition

As IT industries rapidly grow, employees experience increasing stress levels. Despite available mental health support, effectively managing stress remains challenging. This project employs image processing and machine learning techniques to analyze and detect stress patterns in employees.

## Objectives

- Develop an automatic stress detection system using captured images.
- Predict whether an individual is experiencing stress.
- Provide an efficient solution to reduce health risks associated with stress.

## Limitations

- Physiological signals can be non-stationary.
- Difficulty in identifying universal patterns due to varied stress expressions among individuals.

## System Architecture

The project involves two primary phases:

### 1. Model Development Phase:
- Data Collection
- Data Pre-processing and Feature Engineering
- Machine Learning Model Building (K-NN and Logistic Regression)
- Model Training and Evaluation

### 2. Deployment Phase:
- Backend and UI development
- Deployment on platforms such as Heroku using Django

## Technologies Used

- **Programming Language:** Python
- **Frameworks:** Django, Flask
- **Tools:** PyCharm, Visual Studio Code
- **Database:** SQLite
- **Deployment Platform:** Heroku

## Machine Learning Techniques

- **K-Nearest Neighbors (K-NN)**
- **Logistic Regression (LR)**
- **Confusion Matrix** for performance evaluation

## Workflow Overview

- Image captured through user webcam
- Image processing for enhanced digital representation
- Emotion detection based on facial expressions
- Classification of stress using machine learning algorithms
- Results displayed via user-friendly interface

## Implementation

- **Data Preprocessing:** Principal Component Analysis for feature extraction
- **Model Training:** Dataset divided into 80% training and 20% testing
- **Model Evaluation:** Cross-validation performed to optimize accuracy
- **Deployment:** Flask and Django used for backend services, UI developed for interactive experience

## Results and Accuracy

- Achieved an accuracy of approximately 96% using optimized K-NN model.

## Future Work

- Incorporate additional physiological parameters for enhanced accuracy.
- Integrate IoT technologies for continuous monitoring and feedback.
- Expand the model to recognize a wider range of activities and stress indicators.

## Conclusion

The developed system effectively predicts stress levels through automated image analysis and machine learning techniques, significantly aiding stress management and promoting healthier lifestyles.

## References

- Giannakakis, G. et al., Biomedical Signal processing and Control, 2017.
- Nisha Raichur, et al., Detection of Stress Using Image Processing and Machine Learning Techniques, 2017.
- IEEE International Conference on Computational Intelligence and Computing Research, 2018.
- Kaggle Dataset: https://www.kaggle.com/qiriro/stress
