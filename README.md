# CODTECH Internship -task-2

Name: Chandan A  
Company: CODTECH IT Solutions Pvt. Ltd.  
ID: CT6WTWE  
Domain: Embedded Systems  
Duration: February 20th, 2025 – April 5th, 2025  
Mentor: Neela Santhosh   

# Project Title  
Home Automation with Bluetooth 

# Project Overview  
The Home Automation with Bluetooth project allows users to remotely control home appliances using a mobile app via Bluetooth communication.  
The system uses an Arduino Uno microcontroller and a Bluetooth HC-05 module to receive commands and control connected devices (lights, fans, etc.).  

# Key Features  
1. Bluetooth-Controlled Devices  
   - Remotely turn devices ON/OFF using a Bluetooth app  
2. Real-Time Control  
   - Immediate response to user commands  
3. LED Indicator  
   - LED shows the current status (ON/OFF) of the connected devices  
4. Safe and Efficient  
   - Wireless control reduces physical interact

# Components Used  
- Microcontroller: Arduino Uno  
- Bluetooth Module: HC-05  
- Relays: To switch home appliances  
- LED Indicators: To display device status  
- Power Supply: 5V  
- Breadboard and Jumper Wires  

# Working Principle  
1. The Arduino Uno receives Bluetooth signals from the HC-05 module.  
2. The signal is decoded into ON/OFF commands.  
3. The Arduino activates or deactivates the relay, which controls the home appliances.  
4. The LED indicator shows the current status of the appliance.  

# Applications  
- Smart Home Control  
   - Control lights, fans, and other appliances remotely  
- Energy Saving  
   - Reduce unnecessary power usage by switching off appliances remotely  
- Home Security  
   - Control electronic locks via Bluetooth  

# How to Run  
1. Assemble the Circuit  
   - Connect the Arduino, Bluetooth module, and relays according to the circuit diagram.  
   - Ensure proper power supply and connections.  

2. Upload the Code  
   - Use the Arduino IDE to upload the `.ino` file.  

3. Connect Bluetooth  
   - Pair the Bluetooth HC-05 module with your phone.  
   - Use a Bluetooth control app to send ON/OFF commands.  

# Troubleshooting  
1. Bluetooth Not Connecting  
   - Check the module’s RX/TX connections.  
   - Ensure the HC-05 module is powered and visible.  

2. No Response from Appliances  
   - Verify relay wiring and power supply.  
   - Ensure the relays are rated for the appliance voltage.  

# Contributing  
Contributions are welcome!  
If you have any improvements or bug fixes, feel free to fork the repository and submit a pull request.  

# License  
This project is licensed under the MIT License.  

[working model](https://github.com/user-attachments/assets/4fc38f79-10b6-493d-b0d0-82a861fec2d8)

