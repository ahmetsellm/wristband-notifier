This project is a wearable motion-notification system developed as a TÜBİTAK 2209-A research project.
A sensor placed near a doorway detects motion or distance changes and wirelessly transmits this information to a wristband, alerting the wearer without requiring them to be in the same room.
The system was built to help monitor access to potentially dangerous areas for pets or babies at home.


## System Overview

**Transmitter (near the door):** Arduino Uno + HC-SR04 ultrasonic sensor + HC-05 Bluetooth module. Continuously monitors distance and sends a signal when a change is detected.

**Receiver (worn on the wrist):** Arduino Nano + HC-05 Bluetooth module + LED. Receives the wireless signal and lights up the LED as an alert.



## Circuit Schematic

[circuit-schematic - Copy.pdf](https://github.com/user-attachments/files/31245316/circuit-schematic.-.Copy.pdf)
