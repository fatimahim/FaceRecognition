# Facial Recognition and Surveillance Platform

This project is a facial recognition and surveillance platform developed using **Spring Boot**, **VGGFace**, and **Kafka**. The platform allows for real-time identification of individuals through facial recognition, displaying their personal information if registered in the database, or notifying if the individual is not found.

## Features
- **Facial Recognition:** Uses VGGFace model to identify individuals based on facial features.
- **Database Integration:** Stores images and personal information of individuals for identification.
- **Real-Time Identification:** Once an individual presents themselves in front of the camera, the system identifies them and displays their information.
- **Non-Match Detection:** If the individual is not found in the database, a message will inform that the person is not recognized.

## Technologies Used
- **Spring Boot:** Backend framework for building the platform.
- **VGGFace:** Deep learning model for facial recognition.
- **Kafka:** Messaging system for handling events in the platform.
- **Database:** Stores photos and personal information.

## Requirements
- Spring Boot
- Kafka
- VGGFace library
- Database (csv file conatins pictures and informations about each person )
- FastApi

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/fatimahim/FaceRecognition.git
