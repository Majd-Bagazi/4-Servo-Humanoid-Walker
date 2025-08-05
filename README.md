# 4-Servo-Humanoid-Walker
Simple humanoid robot that walks using 4 servo motors and Arduino.

# Humanoid Servo Motion Control Using Arduino Uno

# Objective
This project demonstrates motion control using four servo motors connected to an Arduino Uno. The servos execute a sweeping motion, then stabilize at a neutral angle to prepare for basic robotic walking logic.

# Components
- Arduino Uno  
- 4x Servo Motors (SG90/MG90S)  
- Breadboard  
- Jumper Wires  
- Power Supply (5V Regulated Recommended)

# Circuit Description
| Servo | Signal Pin | Power | Ground |
|-------|------------|-------|--------|
| 1     | D3         | 5V    | GND    |
| 2     | D5         | 5V    | GND    |
| 3     | D6         | 5V    | GND    |
| 4     | D9         | 5V    | GND    |

*Ensure all servos share a common ground. Use external power if servo load is high.*

# Program Flow
- **Initialization**: Define servo pins and attach them  
- **Sweep Motion**: Rotate all servos from 0° to 180° and back  
- **Stabilization**: Set all servos to 90° for neutral posture

# Walking Logic (Outline)
- Servo1 & Servo3 → Simulate legs (alternate motion)  
- Servo2 & Servo4 → Act as arms (counter-balancing)  
- Use delays to sequence movement

# Future Enhancements
- Add walking gait cycles  
- Use sensors for feedback (gyro, distance)  
- Optimize power supply with battery & regulators  
- Design mechanical limbs with hinges & brackets



 Creat By ENG: Majd Omar Bagazi
