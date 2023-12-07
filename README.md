# Drowsiness_HRV_EDA
Sequential model using HRV and a 1D-CNN model for EDA data collected using the Empatica E4.

This project aims to develop an innovative drowsiness detection system using HRV (Heart Rate Variability) and EDA (Electrodermal Activity). A Sequential model and a 1D-CNN model were employed respectively. The primary objective was to create a reliable system capable of monitoring and predicting drowsiness levels in real-time, potentially enhancing driver safety and preventing accidents.

To achieve this, we implemented a comprehensive data collection process. Data was gathered from both the CARLA simulator and a custom map created specifically for this project. The Empatica E4 device captured vital physiological signals such as BVP (Blood Volume Pulse), IBI (Inter-Beat Interval), and EDA. The collected BVP and IBI data were further transformed into HRV using custom code.

The collected HRV and EDA data underwent rigorous preprocessing, analysis, and labeling. Drowsiness levels were accurately classified and assigned to the dataset, forming a valuable training set for subsequent LSTM models.

Two separate machine learning models were built, each tailored to handle the HRV and EDA data. These models underwent extensive training, optimization, and validation to ensure their robustness and effectiveness. Remarkably, the resulting models achieved exceptional test accuracies of 98.28% and 96.32%, respectively, signifying their proficiency in detecting drowsiness in drivers.
