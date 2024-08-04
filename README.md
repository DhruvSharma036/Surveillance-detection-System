# Person Detection and Alert System

## Overview

This project leverages YOLOv8 and OpenCV to monitor a webcam feed, detect people, and send an email alert if someone is detected after 1 AM. The system is designed to work within a Jupyter Notebook environment, displaying the video feed in real-time and stopping once an alert is sent.

## Features

- Real-time person detection using YOLOv8.
- Email alert system triggered if a person is detected after 1 AM.
- Video feed displayed directly in a Jupyter Notebook.
- Automatic cessation of processing once a person is detected and an alert is sent.

## Requirements

- **Python 3.x**
- **YOLOv8**: For object detection.
- **OpenCV**: For video capture and frame processing.
- **IPython**: For displaying video feed in Jupyter Notebook.
- **smtplib**: For sending email alerts.

## Setup

1. **Install Dependencies**:
   - Install the necessary Python packages using `pip install ultralytics opencv-python`.

2. **YOLOv8 Model**:
   - Download the YOLOv8 model weights and ensure the correct file path is provided.

3. **Email Configuration**:
   - Set up email credentials and server details in the code to enable email notifications.

4. **Run the Code**:
   - Execute the provided code within a Jupyter Notebook to start monitoring the webcam feed.

## Usage

- **Monitoring**: The code captures video from the webcam and detects persons using YOLOv8.
- **Alerts**: An email is sent if a person is detected after 1 AM, and processing stops.
- **Exit**: The video feed will stop automatically once a person is detected and an alert is sent.

## Notes

- Ensure that your email provider settings allow sending emails from the script.
- The Jupyter Notebook environment is used for displaying video frames.
- Adjust the YOLOv8 model path and email settings as needed for your setup.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
