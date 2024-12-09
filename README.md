# Smart-Bin-AI

Smart-Bin-AI is an intelligent waste classification system that leverages sensor data and machine learning to classify waste as organic or inorganic. The system is designed to assist in efficient waste management by detecting the moisture level in waste, classifying it in real-time, and controlling the operation of a smart dustbin based on the classification.

The project integrates an Arduino microcontroller for real-time data collection using sensors, and a Random Forest Classifier for AI-based waste classification. It automates the process of waste sorting, thereby promoting sustainability and reducing human effort.

Features

Waste Detection: Detects waste using an ultrasonic sensor and identifies its type (organic or inorganic) based on moisture levels.
Machine Learning Classification: Utilizes a pre-trained RandomForestClassifier to predict waste type based on sensor data.
Automatic Control: Opens or closes the bin lid using a servo motor based on the waste classification.
Real-time Data Logging: Logs moisture levels, predictions, and timestamps to a CSV file for further analysis.
Arduino Integration: Interfaces with an Arduino for real-time sensor data and control of the bin's lid mechanism.
Buzzer Alerts: Emits sound alerts when the bin is full or requires attention.
Project Components

Hardware

Arduino UNO: Microcontroller for controlling sensors and motors.
Ultrasonic Sensor: For detecting proximity and identifying waste presence.
Soil Moisture Sensor: For detecting moisture content in the waste.
IR Sensor: For detecting waste type.
Servo Motor: Controls the opening and closing of the bin lid.
Buzzer: Emits alerts based on waste detection and bin status.

Software

Python: Handles machine learning model, data logging, and communication with the Arduino.
RandomForestClassifier: Used for waste classification based on moisture data.
Serial Communication: For real-time communication between the Arduino and the Python script.
