# README: ESP32-CAM MJPEG to SD Security Camera

This project demonstrates how to set up a **security camera** using the **ESP32-CAM** module, which streams video in **MJPEG format** and stores the footage directly onto an SD card. The setup is designed for simple, low-cost video surveillance systems. It provides an efficient way to capture footage in a lightweight format while saving it for future review.

## Features

- **Video Streaming**: Streams live video in MJPEG format.
- **Footage Storage**: Saves the video stream directly to an SD card.
- **Security Camera Application**: Useful for DIY security setups, home surveillance, or monitoring small areas.
- **ESP32-CAM Integration**: Utilizes the ESP32-CAM module for both video capture and data processing.

## Hardware Requirements

- **ESP32-CAM Module**: This is the core of the project, providing video capture and processing capabilities.
- **SD Card**: To store the video footage.
- **FTDI Programmer**: For flashing the ESP32-CAM module.
- **Jumper Wires**: To connect the ESP32-CAM to the FTDI programmer during setup.
- **Power Supply**: 5V power source to run the ESP32-CAM.

## Software Requirements

- **Arduino IDE**: For programming the ESP32-CAM.
- **ESP32 Board Package**: Install this in Arduino IDE to program the ESP32.
- **MJPEG2SD Code**: Code that captures the video stream in MJPEG format and stores it on the SD card.

## Setup Guide

## Personal Reflection

### Why I Built This Application
I addtion to the neccessity of having security in Phialdephia, I created this ESP32-CAM security camera project to explore the power of IoT devices in real-world applications like home security. The project intrigued me because it combined both hardware and software aspects, allowing me to tinker with embedded systems while also handling video streaming and data storage. 

### What I Learned
Working on this project gave me a much deeper understanding of embedded systems, specifically the ESP32 module, and how to interface it with peripherals like the SD card. I learned a lot about how data is processed in real time and stored efficiently. I also became familiar with MJPEG format, which was a valuable learning experience in video streaming.

Debugging the camera and SD card integration taught me the importance of handling hardware failures gracefully. The project also reinforced the necessity of modular code structure, as I had to manage both video capture and data storage simultaneously.

### Future Plans
Moving forward, I want to enhance this project by:
- **Adding Motion Detection**: Incorporating a PIR sensor or using computer vision to trigger recording only when movement is detected.
- **Remote Access**: Enabling remote access to the live video stream so I can monitor the feed from anywhere.
- **Better Video Compression**: Exploring ways to reduce file sizes and store footage more efficiently.
- **Battery Power**: Making the system portable by adding a battery-powered option.
