
I Have created a dataset on my images on the labelzip folder
# Drowsiness Detection System using YOLOv5 and Python

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Installation](#installation)
5. [Usage](#usage)

## Introduction
This Drowsiness Detection System is built using YOLOv5 and Python to detect drowsy behavior in real-time. It can be used for various applications, including driver monitoring systems and workplace safety.

## Features
- Real-time drowsiness detection using YOLOv5.
- Alerts and notifications when drowsiness is detected.
- Easy-to-use interface for configuring and running the system.
- Support for both image and video input sources.

## Prerequisites
Before using the Drowsiness Detection System, ensure you have the following prerequisites installed on your system:

- Python 3.x: You can download Python from [python.org](https://www.python.org/downloads/).
- GPU (optional but recommended for real-time performance).

## Installation
Follow these steps to set up and run the Drowsiness Detection System:

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Madhavmoudhgal/super-meme.git
## Usage
To use the Drowsiness Detection System, follow these steps:

1. **Configure the System**:
   - Open the `config.yaml` file in the project directory using a text editor of your choice.
   - Customize the configuration settings according to your preferences. You can specify input sources (e.g., camera or video file), alert methods (e.g., sound alert or notification), and drowsiness detection thresholds.

2. **Run the System**:
   - Open a terminal or command prompt.
   - Navigate to the project directory:
     ```bash
     cd drowsiness-detection
     ```
   - Start the Drowsiness Detection System using the following command:
     ```bash
     python main.py
     ```

3. **Monitor for Drowsiness**:
   - The system will begin capturing frames from the specified input source.
   - It will use the YOLOv5 model to detect faces and eyes in each frame.
   - If drowsiness is detected based on predefined criteria (e.g., closed eyes for a certain duration), the system will trigger an alert according to the configured method (e.g., sound an alarm or send a notification).

4. **Terminating the System**:
   - To stop the Drowsiness Detection System, press `Ctrl+C` in the terminal where it's running.

5. **Review Logs** (Optional):
   - The system may log drowsiness detection events. You can review these logs in the `logs` directory for further analysis or reporting.

6. **Adjust Configuration** (Optional):
   - If needed, you can modify the configuration settings in the `config.yaml` file and rerun the system.

7. **Customization** (Optional):
   - Customize the system further by adding your own alert methods, integrating with other systems, or extending the functionality as per your project requirements.

By following these steps, you can effectively use and configure the Drowsiness Detection System for your specific use case.


![WhatsApp Image 2024-09-05 at 21 37 37_c6d2138f](https://github.com/user-attachments/assets/8e00867e-4892-4e60-8475-b5aefb67031d)

