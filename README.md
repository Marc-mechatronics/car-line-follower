# Line Follower Robot Systems

An autonomous line-following robot built as part of the Introduction to Mechatronics Course. The robot detects and follows a visual line on a surface using IR/LDR sensors, a microcontroller, and a dual DC motor system.

## Components
- **Sensors:** IR sensors (LED + Photodiode) for light reflection detection between line and surface
- **Microcontroller:** Arduino UNO — processes sensor data and controls motor outputs
- **Motor Driver:** L293D H-Bridge IC — handles bidirectional DC motor control via PWM signals
- **Motors:** Two DC motors for differential drive steering
- **Power Supply:** 9V battery

## How It Works
1. IR sensors continuously scan for reflectance differences between the black line and white surface
2. Arduino reads digital sensor output (0 = white, 1 = black) and determines robot position
3. Motor speeds are differentially adjusted to steer the robot back onto the line
4. The process repeats in a continuous loop for smooth real-time tracking

## Technologies
`Arduino` `C Programming` `L293D Motor Driver` `IR Sensors` `LDR Sensors` `PWM Control` `Circuit Design`

## Repository Contents
- `/code` — Arduino source code (.ino)
- `/schematics` — Circuit diagrams and wiring layouts
- `/presentation` — Project presentation slides

## Team
Built by a team of 7 students under the supervision of Dr. Aya Abdallah — Faculty of Engineering, Mechatronics Course 2022/2023.
