# 4-Servo-Humanoid-Walker
Simple humanoid robot that walks using 4 servo motors and Arduino.

# Description
This project presents the development of a simple humanoid walking robot using four servo motors controlled by an Arduino board. A basic gait algorithm is implemented to coordinate leg movements, simulating a walking motion similar to that of a human.

---

# Objectives
- Simulate human-like walking using servo motors.
- Develop a basic control algorithm for alternating leg motion.
- Understand servo motor control via Arduino.

---

# Components Used
- Arduino UNO (or compatible board)  
- 4 × SG90 Servo Motors  
- Jumper Wires  
- External Power Supply (if needed)  
- Breadboard (optional)  

---

# How It Works
- Each leg of the robot is controlled by two servos (hip and knee).
- The robot alternates movement between the right and left leg.
- The motion loop simulates a simple forward walking gait.
- All servos start at a neutral 90° position and move to calculated angles for step motion.

---

# Code Summary
- Uses the Arduino `Servo` library.
- Initializes servos to default position.
- Executes walking loop:  
  - Right leg lifts and moves forward.  
  - Left leg follows.  
- All movement is time-controlled using `delay()`.

---

# Demonstration
*A video or images can be added here showing the robot walking.*

---

# Future Improvements
- Add sensors for obstacle detection.  
- Implement smoother gait transitions.  
- Add remote control or Bluetooth connectivity.

---

# Author
*Your Name*  
*Your University / Course / ID (if applicable)*  

 Creat By ENG: Majd Omar Bagazi
