# 🚀 Delphine Ingabire in collaboration with [Ingabire Fabiola](https://github.com/fabiola)


## 👨‍💻 About Me

I'm a Level 3 Computer and Software Engineering student, with a keen focus on software development. My passion lies in creating innovative solutions that solve real-world problems. Currently, I'm pursuing specialized training at Talent4Startup, where I'm honing my skills in Software Embedded Systems.


## 🎯 Portfolio

### Project : Parking Management System

#### Problem:

-Inefficient parking lot utilization: Drivers waste time searching for free spaces, leading to frustration and traffic congestion.
-Lack of real-time information: Difficulty finding available parking spaces, especially during peak hours.
-Manual management: Time-consuming and prone to errors, like misplaced tickets or unauthorized parking.

### Proposed Solution:

-Utilize embedded systems with microcontrollers to manage parking spaces.
-Deploy sensors (ultrasonic, magnetic) to detect vehicle presence in each parking slot.
-Implement a central control unit to process sensor data and maintain real-time parking availability information.
-Develop a user interface (mobile app, display board) to show available spaces.

### Benefits:

-Improved parking space utilization: Drivers can easily find available spaces, reducing search time and traffic congestion.
-Real-time information: Users are informed about parking availability beforehand, leading to better planning.
-Increased efficiency: Automates parking management tasks and reduces reliance on manual processes.

### Project Functionality:

-Parking Space Detection: Sensors continuously monitor parking spaces, sending data to the central control unit.
-Data Processing: The central unit interprets sensor data, updates a database of available spaces, and triggers alerts.
-User Interface (Optional): A mobile app or display board shows real-time parking availability for users.

## 🖥️ Tools requires
### Software:
- Programming Languages:C++
- Frameworks/Libraries: ReactJS
- Tools: Git
- Databases: MySQL, MongoDB
- Tinkercad simulation platform
- Kicad or EasyEda for PCB design
- Twilio account (for SMS notification)
- Google Maps API

  ### Hardware:
 1. Parking Space Sensors:
   - Ultrasonic Sensor: HC-SR04 Ultrasonic Sensor
   - Magnetic Sensor: Reed Switch Sensor
2. Microcontroller/Processor:
   - Arduino Uno R3 (for each entry/exit point)(or other arduino)
3. Communication Module:
   - Wi-Fi Module: ESP8266 Wi-Fi Module (for each Arduino)
4. Access Control System:
   - Servo Motor (for door opening)
   - RFID Card Reader: RFID-RC522 Module (for identifying vehicles)
5. LCD Displays:
   - 16x2 LCD Display Module (for displaying available parking spaces)
6. CCTV Cameras:
   - Webcam or Raspberry Pi Camera Module (for monitoring)
7. Power Supply:
   - battery to power device  
8. Enclosures and Mounting Hardware:
   - 3D printed enclosures for Arduino and other components
   - Mounting brackets, screws, jumper wires and some resistors 220(ohm),two red LED

### Project Functionality:

#### Sensor Data Acquisition:

-This module continuously reads data from the deployed sensors (ultrasonic, magnetic) in each parking space.
-The sensors should be configured to send data at regular intervals or upon detecting a change in state (e.g., car entering/leaving a space).

#### Data Processing Unit:

-This central control unit receives the raw sensor data.
-It interprets the data based on sensor type and pre-defined thresholds (e.g., distance for ultrasonic sensor) to determine if a parking space is occupied or vacant.
-The processed data is then used to update a database or map reflecting the real-time parking availability.

#### Communication:

-This module facilitates communication between the central control unit and other systems.
-It could involve sending parking data to a server for remote monitoring or displaying real-time information on a user interface like a mobile app or a display board.
-Communication protocols like WiFi, Bluetooth, or cellular networks can be used depending on the project's needs.

#### User Interface:

-This module provides a user-friendly interface for displaying real-time parking availability information.
-It could be a mobile app where users can see a map of the parking lot with real-time occupancy status for each space.
-Alternatively, a display board strategically placed in the parking lot can visually represent available spaces.

### Additional Features:

-The system can be extended to integrate with payment systems for automated fee collection. This would require additional modules for secure payment processing and communication with payment gateways.
-Reservation functionality can be added, allowing users to reserve parking spaces in advance through the mobile app.
-The system can collect historical parking data for analysis. This data can be used to identify peak usage times, optimize pricing strategies, or improve resource allocation in the parking lot.

## 📫 How to reach me:

- Email: dephaingabire@gmail.com
- LinkedIn: www.linkedin.com/in/iidepha
- GitHub: Depha56








