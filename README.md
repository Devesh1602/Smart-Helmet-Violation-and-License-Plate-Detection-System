# Smart Helmet Violation and License Plate Detection System

## Overview
This project aims to automate the detection of motorcyclists violating helmet laws using YOLOv8 for number plate recognition and OCR to extract license plate details. It stores detected registration numbers in a database and displays them via a ReactJS frontend. Designed for both live video feeds and uploaded footage, it achieved 95.5% detection accuracy, improving law enforcement efficiency.

## Features
1) Helmet Violation Detection: Detects motorcyclists riding without helmets.
2) OCR Integration: Extracts number plates of violators and stores them in a database.
3) ReactJS GUI: Enables real-time video input or file upload, showing detected violations.
4) Low-Light Detection: Enhanced by 35% through model training.

## Tech Stack
Backend: Python, YOLOv8, OCR, Flask
Frontend: ReactJS
Database: MongoDB
Installation

## Usage
Upload video footage or connect to a live camera feed.
The system will detect motorcyclists without helmets, extract the number plate, and store it in the database.
Access the data via the ReactJS interface.

## Results
Detection Accuracy: 95.5%
Violation Detection Improvement: 60%
Low-Light Detection Boost: 35%
