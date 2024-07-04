# Smart Home Implementation using Cisco Packet Tracer

## Overview

This project demonstrates the implementation of a Smart Home using Cisco Packet Tracer. The Smart Home is designed to enhance safety, comfort, and efficiency by automating home activities through various smart sensors and devices connected to the internet.

## Supervisors

- Dr. Ahmed ELdeib
- Eng. Amel Mohamed

## Authors

- Ziad Mohamed El-Sayed (ID: 20176012)
- Abdelrahman Sherief Mohamed (ID: 20176119)
- Ganna Ehab (ID: 20176480)
- Bassel Yasser Sayed (ID: 20176603)

## Introduction

The Internet of Things (IoT) optimizes life by integrating smart sensors and devices that operate together via the internet. This project focuses on creating a Smart Home that uses various sensors (temperature, humidity, smoke, wind, sound) to monitor the home environment and provide automatic security using alarm systems, LCD displays, sirens, and email notifications.

## Components

The following components are used in the Smart Home implementation:

1. **Home Gateway**: Connects and controls other objects and sensors, providing a programming environment for these devices.
2. **Smartphone**: Connects to the Home Gateway to give orders and set conditions for each object.
3. **Other Components**: Chic windows, chic fans, chic lights, chic doors, chic garbage doors, lawn sprinklers, fire sprinklers, webcams, motion detectors, cars, carbon dioxide detectors, and smoke detectors.

## Steps to Implement

1. **Connect Home Gateway and Smartphone**:
    - Drag the Home Gateway and Smartphone into the workspace.
    - Connect the Home Gateway to the Smartphone by copying the SSID name from the Home Gateway to the phone.

2. **Add Components**:
    - Drag necessary components into the workspace.
    - Connect each component to the Home Gateway:
        - Go to the component's configuration.
        - Choose "IoT server" and select "Home Gateway".
        - Click on "Advanced" and select "I/O config".
        - Choose the PT-IOT-NM-1W option to connect the object to the Home Gateway.

3. **Rename Components**:
    - Rename all components to easily identifiable names for proper implementation.

4. **Set Conditions Using Smartphone**:
    - Open the Smartphone.
    - Click on "Desktop".
    - Choose "IoT Monitor".
    - Set conditions for each component as needed.

## Sample Conditions

- ROOM1 ON
- ROOM1 OFF

Detailed conditions can be found in the project attachment in the CPT file.

## Final View

After connecting and setting conditions for all components, the Smart Home project is successfully implemented, demonstrating the integration and automation of various smart devices.
