# AgroVision
An AI-IoT System for Plant Health Detection for Optimized Agrochemical Use.

# Introduction
The fundamental element of our AI-IoT System is an autonomous mobile robot platform that moves in agricultural fields on its own and takes real-time photos of plants with an ESP32-CAM module. The images are then processed and analyzed on the basis of YOLOv8 (You Only Look Once, version 8), an advanced object detection model renowned for its precision and real-time inference performance. YOLOv8 detects infected areas in the images taken and classifies them immediately, enabling farmers to identify plant diseases at an early stage and take appropriate action on time.
The system uses OpenCV for pre-processing operations like contrast adjustment and noise removal to enhance detection quality. An Arduino Uno microcontroller controls the movement of the robot. Wireless data transfer is facilitated through ESP32, which makes the system appropriate for remote monitoring without constant physical observation.
Key Outcomes
The key outcomes of this project include:
Real-time and accurate detection of plant diseases using YOLOv8
Autonomous field navigation and image acquisition
Reduced manual labor and human error
Support for sustainable and precision agriculture through targeted intervention
Support for eco-friendly farming practices.

# Key technologies used include: 
- YOLOv8 
- OpenCV
- Python
- Arduino IDE
- ESP32-CAM
- 4WD robotic platform
# AgroVision Pipeline Flowchart: 
![agro](https://github.com/user-attachments/assets/c01ba903-12bc-4373-99fe-d2d8e4b2ee22)

- Start Monitoring: The system initializes the robot and camera, starting the monitoring process.
- Capture Image: As the robot moves, the camera captures images of plants.
- Send Image to Processing Unit: The captured image is sent to the laptop or cloud via Wi-Fi.
- Analyze Image with YOLOv8: The AI model (YOLOv8) processes the image and detects any signs of disease.
- End Monitoring: Once the area is covered, the robot stops.


