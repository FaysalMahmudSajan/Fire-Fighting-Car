# Fire Fighting Car & Alert System

<p align="center">
  <img src="https://github.com/Faysal3010/Fire-fight-car/blob/main/WhatsApp%20Image%202026-01-24%20at%202.47.11%20PM.jpeg" width="600"/>
  <img src="https://github.com/Faysal3010/Fire-fight-car/blob/main/WhatsApp%20Image%202026-01-24%20at%202.49.36%20PM.jpeg" width="600"/>
</p>


### video : https://youtu.be/KEN8z2rMZEw?si=6TZl8V0_H2nbCSly

An Arduino-based smart fire fighting robot that automatically detects fire, moves toward it, and extinguishes it using a water pump.  
The system also detects smoke/alcohol gas and provides an alert using a buzzer.

This project demonstrates automation, embedded systems, and real-time fire safety mechanisms.

---

## Project Overview

The Fire Fighting Car is designed to:

- Detect fire using flame sensors
- Navigate automatically toward the fire source
- Spray water to extinguish the fire
- Detect smoke or alcohol gas
- Trigger an alert system

It works without human intervention and can be used in small indoor environments for fire safety.

---

## Main Components

- Arduino (Main Controller)
- Flame Sensors (3x)
- DC Motors (2x)
- Motor Driver Module
- Water Pump
- Water Tank
- Smoke/Alcohol Gas Sensor
- Buzzer
- Chassis/Robot Car Body
- Battery

---

## Working Concept

### Fire Detection
- Three flame sensors are placed:
  - Left
  - Middle
  - Right
- Sensors continuously monitor fire presence.

### Movement Logic
- If left sensor detects fire → move left
- If right sensor detects fire → move right
- If middle sensor detects fire → move forward
- Two DC motors control movement

### Fire Extinguishing
- When the robot reaches the fire:
  - Water pump turns ON
  - Water sprays on the fire
  - Servo/wiper spreads water left and right
- After fire is extinguished → system stops

### Smoke/Alcohol Detection
- Gas sensor monitors smoke/alcohol
- If detected:
  - Buzzer alert turns ON
  - Warning signal provided

---

## Features

- Automatic fire detection
- Direction-based navigation
- Water spraying system
- Smoke and alcohol detection
- Audio alert system
- Low-cost hardware
- Real-time response

---

## Pin Configuration (Example)

| Component | Arduino Pin |
|-----------|-------------|
| Left Flame Sensor | D2 |
| Middle Flame Sensor | D3 |
| Right Flame Sensor | D4 |
| Motor Driver | D5-D8 |
| Water Pump | D9 |
| Gas Sensor | A0 |
| Buzzer | D10 |

(Modify based on your setup)

---

## Project Structure


#https://www.canva.com/design/DAF3zfKW1XY/AH8GGUxsr_4qmv9y6fgE_g/edit
