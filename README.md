# Crop-health-monitoring-system-using-ML-
Crop Health Monitoring using PlantVillage Dataset

This project aims to classify plant leaves as Healthy or Unhealthy using traditional machine learning techniques. Instead of directly applying deep learning, meaningful image features were manually extracted and analyzed to understand their contribution to disease detection.

Features Extracted
Color Features: Mean RGB and HSV values
Texture Features: GLCM-based Contrast, Homogeneity, Energy, and Correlation
Shape Features: Area and Perimeter using contour detection
Spot Features: Disease spot count and affected area

Workflow
Dataset exploration and preprocessing
Image resizing and feature extraction
Feature analysis using correlation matrix
Feature scaling and train-test split
Random Forest model training
Performance evaluation using confusion matrix and accuracy metrics

Results
Binary Classification: Healthy vs Unhealthy
Model: Random Forest Classifier
Accuracy: ~79.5%

Technologies Used
Python
OpenCV
NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
