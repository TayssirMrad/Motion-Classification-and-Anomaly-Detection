# Motion-Classification-and-Anomaly-Detection
- Overview:
A project focused on implementing an embedded machine learning system for classifying motion and vibration data from various machines. The objective is to detect operational modes and anomalies without modifying the machine.

- Objective:
Develop a machine learning system capable of categorizing machine states such as off, on, low load, high load, and anomalies using motion and vibration data.

1 - Data Collection :
Used a phone app to generate vibration then collect accelerometer data for different states. Label and gather sufficient data for both training and testing.

2 -Feature Extraction:
Employ Spectral Analysis, Neural Network, and K-means Anomaly Detection for feature extraction. 

3- Model Training:
Train the Neural Network model, adjust hyperparameters if necessary, and ensure accuracy within acceptable ranges.


4-Anomaly Detection:
Train an Anomaly Detection model using selected features for identifying unusual patterns in the data.

5- Model Testing:
Evaluate the trained model's performance on test data, making adjustments to improve accuracy. 
![test_model](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/d9cf05c9-f3ae-4472-ab2d-be9afb432ce2) 

6-Deployment:
Deploy the model on the  Arduino board and test its ability to classify machine states in real-time.
