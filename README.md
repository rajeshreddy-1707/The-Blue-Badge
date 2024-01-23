# The-Blue-Badge


## Introduction

The Visually Impaired Assistance System is an Android application developed to assist visually impaired individuals in navigating unfamiliar environments using advanced technologies such as machine learning, computer vision, and speech recognition.

## Motivation

Navigation can be a significant challenge for visually impaired individuals, limiting their mobility and independence. This project aims to empower this community by providing a user-friendly app that offers real-time audio instructions and information to help them navigate confidently.

## Objective

The primary objective of this project is to develop a user-friendly and intuitive app that utilizes advanced technologies  like object detection, distance estimation, and text-to-speech conversion to assist visually impaired individuals in navigating unfamiliar environments.

## Working Principle

The system's working principle involves three main components:
1. **Image Detection**: Utilizing the YOLOv7 object detection model to identify and detect objects in real-time.
2. **Distance Estimation**: Using geometry to estimate the distance from the camera to detected objects.
3. **Speech Recognition**: Converting the text output into speech using the 'pyttsx3' Python package.

## Components

The project comprises the following key components:
- Image Detection
- Distance Estimation
- Speech Recognition
- Android App Integration

## Individual Contributions

- **Mohd Mohsin Khan (20BAI10340)**
    - Distance Detection: Implemented and fine-tuned the distance estimation algorithm.
    - Speech Recognition: Researched and integrated the 'pyttsx3' package for text-to-speech conversion.

## Installation

To install and run the Android app, follow these steps:
1. Clone the repository to your local machine.
2. Open the project in Android Studio.
3. Build and run the app on an emulator or a physical Android device.

## Usage

- Open the app on your Android device.
- Point the camera at objects in your environment.
- The app will provide real-time audio instructions and information about the objects detected.

## Future Enhancements

Future enhancements for the project may include:
- Lightweight object detection for improved performance on mobile devices.
- AutoML integration to automate model design.
- Domain adaptation for handling non-i.i.d. data.
- Weakly supervised detection to reduce annotation efforts.
- Small object detection for specialized applications.
- Real-time object detection and tracking in videos.

## System Architecture 

<img width="469" alt="image" src="https://github.com/mohdmohsin0403/The-Blue-Badge/assets/78999231/fdd7a2f6-c5a3-46ab-938c-f918d16354e1">


## Acknowledgments

We would like to acknowledge the support and feedback from the visually impaired community and the contributors to the open-source tools used in this project.

## Project Outcomes

**Outcome 1**: Saves time by detecting obstacles beforehand and avoiding accidents or crashes.

**Outcome 2**: Assists people who take care of visually impaired individuals by providing an extra layer 
of safety on the road.

**Outcome 3**: Prototype of the system is developed which measures and monitors road conditions from 
a distance of about 3 meters from the obstacle.

**Outcome 4**: Notifies the driver of any sudden movement of obstacles that may pose a threat, leading 
to a decrease in the speed of the vehicle and avoidance of accidents or crashes.

**Outcome 5**: Develops a system for the detection and recognition of various poses of the objects and 
tracks them efficiently, ensuring that the system is reliable and accurate.

**Outcome 6**: Helps those who can't afford eye operations, power glasses, or lenses by providing a lowcost project approach that ensures safety on the road.
