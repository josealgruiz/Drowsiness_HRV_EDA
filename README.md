# Drowsiness_HRV_EDA
LSTM using HRV and EDA data collected using the Empatica E4

This project aims to develop an innovative HRV (Heart Rate Variability) and EDA (Electrodermal Activity) LSTM (Long Short-Term Memory) model for detecting drowsiness in drivers. The primary objective was to create a reliable system capable of monitoring and predicting drowsiness levels in real-time, potentially enhancing driver safety and preventing accidents.

To achieve this, a comprehensive data collection process was implemented. Data was gathered from both the CARLA simulator and a custom map created specifically for this project. The Empatica E4 device captured vital physiological signals such as BVP (Blood Volume Pulse), IBI (Inter-Beat Interval), and EDA. The collected BVP and IBI data were further transformed into HRV using a custom code.

The collected HRV and EDA data were then subjected to rigorous preprocessing, analysis, and labelling. Drowsiness levels were accurately classified and assigned to the dataset, forming a valuable training set for the subsequent LSTM models.

Two separate LSTM machine learning models were built, each tailored to handle the HRV and EDA data. These models underwent extensive training, optimization, and validation to ensure their robustness and effectiveness. Remarkably, the resulting models achieved exceptional test accuracies of 96% and 97% respectively, signifying their proficiency in detecting drowsiness in drivers.
