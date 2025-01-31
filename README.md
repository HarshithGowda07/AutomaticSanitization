# AutomaticSanitization using line-following robot

**#Introduction**

During the COVID-19 pandemic, maintaining hygiene and minimizing human contact became critical to reducing the spread of the virus. One of the key measures was the frequent use of hand sanitizers. However, manual sanitization processes often required human intervention, which could lead to cross-contamination or inefficiency.

To address this issue, we developed an Automatic Sanitization Line-Following Robot. This robot is designed to autonomously follow a predefined path while continuously sanitizing the surrounding area, eliminating the need for manual intervention and ensuring consistent and efficient sanitization.

**#Objective**

The primary objective of this project is to create an autonomous robot that:
Follows a Line: Uses IR sensors to detect and follow a predefined path (e.g., a black line on a white surface).
Sanitizes Continuously: Dispenses sanitizer automatically while moving, ensuring thorough coverage of the area.
Reduces Human Contact: Minimizes the need for manual sanitization, reducing the risk of contamination.

**#Working Principle**

The robot operates based on the following principles:

Line Following:

The robot uses IR sensors to detect a line on the ground.
Based on the sensor inputs, the robot adjusts its movement to stay on the path.
If the middle sensor detects the line, the robot moves forward.
If the left or right sensor detects the line, the robot turns left or right, respectively.

Sanitization:

A sanitizer sprayer (controlled by a servo motor or pump) is mounted on the robot.
As soon as the robot starts moving, the sprayer is activated and continuously dispenses sanitizer.
The sprayer stops only when the robot stops, ensuring efficient use of sanitizer.

Autonomous Operation:

The robot operates autonomously, requiring no human intervention once it is started.
It is powered by an Arduino Uno microcontroller, which processes sensor data and controls the motors and sprayer.

**#Components Used**

Arduino Uno: The brain of the robot, used to control all components.
IR Sensors: Detect the line and guide the robot's movement.
L298N Motor Driver: Controls the DC motors for movement.
DC Motors: Drive the robot's wheels.
Servo Motor/Pump: Controls the sanitizer sprayer.
Chassis: The body of the robot, which holds all components.
Battery: Provides power to the robot.
Sanitizer Dispenser: Stores and dispenses sanitizer.

**#Advantages**

Contactless Sanitization: Eliminates the need for human intervention, reducing the risk of contamination.
Efficient Coverage: The robot sanitizes the area thoroughly as it moves along the path.
Cost-Effective: Uses low-cost components and can be easily replicated.
Scalable: Can be deployed in various environments, such as hospitals, offices, and public spaces.

**#Applications**

Hospitals and Clinics: For sanitizing corridors, waiting areas, and patient rooms.
Offices and Workspaces: For maintaining hygiene in common areas.
Public Spaces: For sanitizing parks, malls, and transportation hubs.
Educational Institutions: For sanitizing classrooms and hallways.

**#Future Enhancements**

Obstacle Avoidance: Integrate ultrasonic sensors to detect and avoid obstacles.
Remote Control: Add Bluetooth or Wi-Fi connectivity for remote operation.
Advanced Sanitization: Use UV-C light or mist sprayers for more effective sanitization.
Battery Monitoring: Implement a battery level indicator to notify when the robot needs recharging.

**#Conclusion**

The Automatic Sanitization Line-Following Robot is a practical and innovative solution to the challenges posed by the COVID-19 pandemic. By automating the sanitization process, it ensures consistent hygiene while minimizing human contact. This project demonstrates the potential of robotics and automation in addressing real-world problems and improving public health.
