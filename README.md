# Integrated-Omni-Directional-Mobile-Platform-with-Ball-Balancing-System
## 1. Project Overview
three-wheeled omni-directional mobile base A ball balancing system mounted on top This project presents an integrated robotic platform consisting of: The system demonstrates advanced sensor–actuator integration and real-time control.
## 1. Project Overview
The system demonstrates practical integration between sensing elements and actuators to achieve stable physical behavior under dynamic conditions.
![image](https://github.com/user-attachments/assets/1a816749-c8d1-4663-8f2d-9cc733a89c46)

## 2. Educational Objectives
The main educational goals of this project are:
- Applying sensor selection and interfacing techniques
- Understanding actuator behavior and limitations
- Integrating sensors and actuators within a robotic platform
- Translating theoretical course concepts into a practical system

## 3. System Description
The robotic platform is composed of two main subsystems:
1. An omni-directional mobile base driven by DC motors.
2. A ball balancing system mounted on top, capable of tilting in two axes.

The platform is designed to operate as a unified system where sensor measurements are continuously used to drive actuator responses.

## 4. Sensors
The following sensors were utilized in the system:

### 4.1 Resistive Touch Panel
A 4-wire resistive touch panel was used as the primary sensor for ball position detection. The panel provides analog voltage outputs corresponding to the ball position in the X and Y directions. This sensor was selected due to its low latency, simple interfacing requirements, and robustness against lighting conditions.

### 4.2 Inertial Measurement Unit (IMU)
An IMU sensor was used to monitor the orientation of the platform and detect motion-related disturbances. This information supports the overall sensing capability of the system during operation.

## 5. Actuators
The system employs the following actuators:

### 5.1 RC Servo Motors
RC servo motors are used to control the tilt of the ball balancing plate along the pitch and roll axes. These actuators provide high positioning accuracy and fast response, making them suitable for dynamic balancing tasks.

### 5.2 DC Motors
DC motors are used to drive the omni-directional mobile base. The motors are controlled through an L298N motor driver, enabling directional control and speed regulation.

## 6. Control and Electronics
The system utilizes an Arduino microcontroller for real-time sensor data acquisition and low-level actuator control. A Raspberry Pi is used for higher-level processing and system coordination. This separation allows reliable real-time operation while maintaining system flexibility.

## 7. System Integration
The project emphasizes proper integration between sensors, actuators, controllers, and drivers. Sensor data is processed and used to generate actuator commands in real time, allowing the system to respond effectively to physical disturbances and motion.

## 8. Repository Structure
The repository is organized to clearly separate hardware design, sensor interfacing, actuator control, and documentation, facilitating readability and future development.

## 9. Team Members
- Mohamed Gamal Zain  
- Mohammed Abdelsabour  
- Kareem Shaban Eid  
- Mohamed Hamada  

## 10. Course Information
- Course Title: Sensors and Actuators (MTE 434)  
- Presented to: Dr. Mohamed Adel  

## 11. License
This project is intended for educational and academic use only.
