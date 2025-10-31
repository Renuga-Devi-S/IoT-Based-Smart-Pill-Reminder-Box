# IoT-Based-Smart-Pill-Reminder-Box

## Abstract

The IoT-Based Smart Pill Reminder and Monitoring Device is an innovative healthcare system designed to help patients take their medication on time. Using an ESP32 microcontroller, it integrates components like an RTC module, RFID, IR sensor, LCD display, and buzzer to issue real-time alerts and confirm pill intake. The system records dosage events automatically and minimizes human error. This project combines IoT and embedded systems to deliver a low-cost, reliable, and user-friendly solution for improving medication adherence and patient safety.

## Hardware Requirements

* ESP32 Microcontroller – main controller with Wi-Fi and Bluetooth
* IR Sensor – detects pill removal
* RFID Module (RC522) – authenticates the user
* LCD Display (16x2) – displays time and messages
* Load Cell + HX711 Amplifier – measures pill weight for confirmation
* Buzzer + Amplifier – provides audible alerts
* Potentiometer – adjusts sensor sensitivity and display contrast
* Breadboard & Jumper Wires – for circuit prototyping and connections

## Software Requirements

* Arduino IDE – used for programming and uploading code to ESP32
* Embedded C/C++ Libraries – for sensor, LCD, and RFID interfacing
* Serial Monitor – for debugging and testing sensor output

## About the Project

This project aims to automate medication management through an intelligent pill reminder device. It alerts users at preset times, verifies pill consumption, and logs the data for monitoring. The ESP32 acts as the brain of the system, processing inputs from sensors and controlling outputs such as the display and buzzer. The system is ideal for elderly patients or individuals with chronic illnesses who may forget or delay medication. Future versions can integrate mobile apps, cloud storage, and AI-based analytics for advanced monitoring.

## Pictures 
<img width="474" height="255" alt="image" src="https://github.com/user-attachments/assets/b48b6347-4935-49da-ad32-96f57696cc16" />
<img width="477" height="262" alt="image" src="https://github.com/user-attachments/assets/1e0fdf93-f2ce-42aa-a329-9f3ceb0a7b48" />
<img width="479" height="262" alt="image" src="https://github.com/user-attachments/assets/3e52adbd-0778-4264-a19e-a2d144c0d612" />
<img width="479" height="262" alt="image" src="https://github.com/user-attachments/assets/521e2cbf-062f-4280-a9da-688aae47931a" />

