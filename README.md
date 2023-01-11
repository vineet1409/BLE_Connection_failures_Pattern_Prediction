# BLE_Connection_failures_Pattern_Prediction

## Problem Statement
•	The production line team was facing regular BLE connection failures between wearable devices like Fitbit and BLE receiver(Phone) thereby leading to loss of real time sensor data (BLE packets). The team wanted to identify the important metrices and understand the pattern behind connection loss.
•	The task was to create a pipeline to analyze the metrices from sniffed BLE packets and perform quick analytics. A predictive classification-based machine learning model was to be designed to predict the connection failures based on identified critical parameters during packet exchange between BLE Transmitter (Wearable device) and Receiver (Phone).

## Architecture
![Architecture](/Architecture/aws_glue_project_fitbit.jpg)