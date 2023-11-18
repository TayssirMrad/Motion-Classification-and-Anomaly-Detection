# Motion-Classification-and-Anomaly-Detection
- Overview:
A project focused on implementing an embedded machine learning system for classifying motion and vibration data from various machines. The objective is to detect operational modes and anomalies without modifying the machine.

- Objective:
Develop a machine learning system capable of categorizing machine states such as off, on, low load, high load, and anomalies using motion and vibration data.

- Setup:
Before I started collecting data, I connected the Arduino board. I ran the flash script in the .zip file (used .bat for Windows) to upload the EI firmware to the Arduino. After the flashing was complete, I pressed the reset button on the Arduino board. I then went back to my Edge Impulse project and verified that the Arduino board was connected.
![arduino](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/4f267675-46e5-4300-ac7f-993709ec959b)



1 - Data Collection :

Used a phone app to generate vibration then collect accelerometer data for different states. Label and gather sufficient data for both training and testing.

![Screenshot 2023-11-15 233157](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/0bb6db28-da11-435b-8faf-611e01e055e9)

2 -Feature Extraction:

Employ Spectral Analysis, Neural Network, and K-means Anomaly Detection for feature extraction. 

![Screenshot 2023-11-15 233415](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/20aa4517-948e-42f2-920d-124273da87c8) 

Generating features :

![Screenshot 2023-11-10 160321](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/b2dd04c8-2b4b-47cd-adb6-8f9258e81c9a)

3- Model Training:
Train the Neural Network model, adjust hyperparameters if necessary, and ensure accuracy within acceptable ranges.

![test_model](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/d9cf05c9-f3ae-4472-ab2d-be9afb432ce2) 

NN Classifier :

![edge_impulse](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/6a80403f-6f3d-4ace-a210-bacfc95a8274)

4-Anomaly Detection:
Train an Anomaly Detection model using selected features for identifying unusual patterns in the data.

![edge impulse2](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/9bb52489-72a4-4f45-abef-d0554c6cf07c)


5- Model Testing:
Evaluate the trained model's performance on test data, making adjustments to improve accuracy. 

![image](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/d06e1aad-d838-49bf-a8e0-6b1a72ca08ed)

6-Deployment:
Deploy the model on the  Arduino board and test its ability to classify machine states in real-time.

![image](https://github.com/TayssirMrad/Motion-Classification-and-Anomaly-Detection/assets/60198040/00606265-f21d-4470-ab6f-059319edbdb2)

