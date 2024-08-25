# Autonomous Car System with ML and IoT Integration

## Project Overview

This project focuses on developing an Autonomous Car System that leverages Machine Learning (ML) and Internet of Things (IoT) technologies to enable self-driving capabilities. The system is designed to autonomously navigate by processing real-time data from various sensors, ensuring safe and efficient driving.

## Key Features

- **Real-time Object Detection:**
  - **Objective:** Utilize advanced ML algorithms to detect and classify objects in the car’s environment.
  - **Importance:** Ensures safe navigation by recognizing pedestrians, vehicles, and obstacles.

- **Path Planning:**
  - **Objective:** Implement reinforcement learning to determine the optimal driving path.
  - **Importance:** Adapts to dynamic obstacles and traffic conditions for efficient navigation.

- **IoT Integration:**
  - **Objective:** Equip the system with IoT devices for continuous sensor data collection and real-time decision-making.
  - **Importance:** Facilitates seamless data transfer and communication between vehicle components.

## Technologies Used

- **Machine Learning:**
  - **Role:** Applied for object detection and path planning.
  - **Benefit:** Enhances the vehicle’s ability to interpret surroundings and make informed decisions.

- **IoT:**
  - **Role:** Provides real-time data acquisition and system communication.
  - **Benefit:** Enables adaptive and responsive driving behaviors.

- **Embedded Systems:**
  - **Role:** Manages the car’s hardware components.
  - **Benefit:** Ensures efficient control and integration of sensors, motors, and other elements.

## Methodology

### Hardware Design

- **Arduino Microcontroller:**
  - **Purpose:** Core control unit for interpreting sensor data and regulating motor functions.
  - **Choice:** Arduino Uno for its versatility and user-friendliness.

- **Infrared (IR) Sensors:**
  - **Purpose:** Detect the black line on a white surface for path following.
  - **Mechanism:** Measures reflected infrared light to maintain track alignment.

- **DC Motors and Motor Driver:**
  - **Purpose:** Drive the vehicle and control speed and direction.
  - **Mechanism:** Motors are controlled by an L298N driver module for direction and PWM speed regulation.

- **Chassis and Power Supply:**
  - **Purpose:** Securely house all components.
  - **Design:** Includes mounting points for components and a battery pack for power.

### Software Development

- **Initialization:**
  - **Purpose:** Configure digital pins for IR sensors and motors.
  - **Details:** Sets up sensors as input pins and motors as outputs with PWM speed control.

- **Main Loop:**
  - **Purpose:** Implement line-following logic.
  - **Details:** Reads sensor data to adjust motor speed and direction for navigation.

- **Motor Control Function:**
  - **Purpose:** Adjust motor direction and speed.
  - **Details:** Processes data to control motor behavior using digital signals and PWM.

### System Integration

- **Hardware Assembly:**
  - **Process:** Assemble and secure hardware components on the chassis, including sensors and motors.

- **Software Upload:**
  - **Process:** Upload the code to the Arduino using the Arduino IDE to control sensors and motors.

- **Testing and Calibration:**
  - **Process:** Test the vehicle on a track with varied sections. Calibrate motor speed and sensor sensitivity to ensure optimal performance.

## Outcome

The project successfully integrates ML and IoT technologies to create an autonomous vehicle capable of navigating diverse tracks. It demonstrates the potential for efficient and reliable self-driving solutions, showcasing practical applications and addressing challenges in autonomous driving systems.

##Some Snapshots of Project:
![image](https://github.com/user-attachments/assets/fb4f6fe7-4511-4a67-91d8-f900fef2d5a1)
