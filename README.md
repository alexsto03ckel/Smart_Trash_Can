# Smart Trash Classifier

## Overview
The Smart Trash Classifier is an embedded system that automatically sorts waste into three categories: CAN, PLASTIC, and OTHERS. It uses a Wio Terminal with a machine learning-based sound classification model (developed in Edge Impulse) to analyze the sound of trash being thrown. Based on the classification, servo motors position a rotating container under the gate and open it to drop the waste into the correct compartment.

## Components
- **Hardware**: Wio Terminal, Arduino Uno, MG996R servos, breadboard, 9V battery.
- **Software**: Arduino IDE, Visual Studio, Edge Impulse.

## How It Works
1. Trash is dropped through a servo-controlled gate.
2. The Wio Terminal analyzes the sound and classifies the waste.
3. The Arduino Uno directs servo motors to rotate the container and align the correct compartment.
4. The gate opens, allowing the trash to fall into the assigned section.

## Installation & Usage
1. Connect and assemble hardware components.
2. Upload the code to the Wio Terminal and Arduino Uno.
3. Deploy the trained model from Edge Impulse.
4. Power the system and test classification.

## License
This project is licensed under the MIT License.

## Acknowledgments
Developed as part of an embedded systems design project 

