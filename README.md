CAN-Based Automotive Dashboard
📌 Project Overview

The CAN-Based Automotive Dashboard is an Embedded C project that simulates a vehicle dashboard using the PIC18F4580 microcontroller. It uses the CAN protocol to transmit and receive real-time vehicle data such as speed, RPM, gear position, and indicator status between multiple ECUs and displays the information on a 16×2 CLCD.

🚀 Features
Real-time transmission and reception of vehicle parameters using the CAN protocol
Displays speed, RPM, gear position, and indicator status on a 16×2 CLCD
Multi-ECU communication using CAN message IDs
Reads sensor data and updates the dashboard in real time
Modular Embedded C implementation for easy maintenance
🛠 Tech Stack
Language: Embedded C
Microcontroller: PIC18F4580
Protocol: CAN (Controller Area Network)
Peripherals: CLCD, ADC, Digital Keypad
IDE: MPLAB X IDE
Compiler: XC8 Compiler
🔄 Program Flow

Read Vehicle Data → Transmit Data via CAN → Receive CAN Messages → Process Vehicle Parameters → Display Speed, RPM, Gear, and Indicator Status on CLCD

⚠️ Challenges Faced
Configuring CAN communication between multiple ECUs
Ensuring reliable real-time data transmission
Synchronizing multiple vehicle parameters on the dashboard
Debugging CAN messages and peripheral interfaces
🎓 Learning Outcomes
Learned CAN-based communication between ECUs
Gained hands-on experience with Embedded C and PIC18F4580
Improved knowledge of CLCD interfacing and real-time embedded systems
Enhanced debugging, modular programming, and firmware development skills
