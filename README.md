# VR Physical Therapy Gloves

## Overview
This project was part of a larger concept exploring virtual reality-assisted physical therapy, where interactive VR environments could be used to guide rehabilitation exercises. The Arduino-based wearable system reads finger position using potentiometers and drives micro servos to support finger extension, forming a closed-loop control system.

## System Design
Input (potentiometers) → Arduino processing → Output (micro servos)

The system continuously reads analog input from the potentiometers and adjusts servo positions to assist movement in real time.

## Hardware
- Arduino (microcontroller)
- Potentiometers (finger position sensing)
- Micro servos (actuation)
- Glove structure for mounting components

## Software
- Written in C++
- Reads analog sensor values from potentiometers
- Maps input values to corresponding servo positions
- Updates servo output to assist finger extension

## My Contributions
- Implemented control logic in C++ for sensor-to-servo interaction
- Integrated potentiometer input with servo actuation
- Tested and adjusted system behavior to improve responsiveness and consistency
- Helped validate overall system functionality against intended use

## Testing & Debugging
- Tested system response to different input ranges to ensure smooth servo movement
- Adjusted mapping and control logic to reduce inconsistent or delayed responses
- Verified hardware connections and signal behavior during system operation

## Results
The system was able to respond to finger position input and assist movement through servo actuation. Testing focused on improving responsiveness and ensuring consistent behavior.

## Additional Documentation
See attached project poster for system design, build process, and results.
<img src=https://github.com/irania0201/VR-Physical-Therapy-Gloves/blob/main/Dynamic%20VR%20PT%20Gloves%20Poster.jpg width="975">
