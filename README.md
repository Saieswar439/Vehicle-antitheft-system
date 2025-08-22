# Vehicle-antitheft-system
A smart anti-theft system using **Arduino Uno, Fingerprint Sensor (R307S), GSM (SIM808), and GPS tracking**
# Project Objective
In this rapidly advancing technological era, the demand for efficient vehicle security systems is at an all-time high. This project presents a robust vehicle anti-theft system integrating fingerprint recognition and SMS-based owner authentication, and vehicle live tracking. The system employs a fingerprint scanner to verify the identity of the individual attempting to access the vehicle. Upon detecting an unauthorized fingerprint, an SMS is sent to the vehicle 
owner's registered mobile number, requesting their approval to start the vehicle. The owner can respond with an "ACCEPT" or "DENY" message, enabling or disabling the ignition system, respectively. This approach not only ensures robust biometric authentication but also allows the owner to remotely control vehicle access, adding an extra layer of security. The system is implemented using a Aurdino UNO, GSM module, fingerprint scanner, and a relay module for ignition control. This advanced solution provides a reliable, cost-effective, and user-friendly approach to vehicle theft detection. 

## 🔧 Features
- Fingerprint-based ignition control
- SMS alerts on unauthorized access
- Remote start/stop via SMS (ACCEPT/DENY)
- Location tracking via GPS (Google Maps link)
- Low-cost and user-friendly design

 ## SYSTEM DESIGN
- The Fingerprint-Based Vehicle Anti-Theft System integrates biometric authentication with remote communication to secure a two-wheeler. 
The system uses an R307S fingerprint sensor to verify the user’s identity, allowing only authorized individuals (with pre-registered fingerprints) to start the vehicle. 
- If an unauthorized fingerprint is detected, the system sends an SMS alert to the owner’s registered mobile number via the SIM808 module, which also provides GPS functionality for live tracking. 
- The owner can respond with predefined commands (e.g., ACCEPT, DENY) to control the vehicle’s ignition remotely. 
- An Arduino Uno microcontroller oversees the system, managing the fingerprint sensor, SIM808 module, a relay for ignition control, a buzzer for alerts, and a 16x2 LCD for status display. 
- The system is powered by a 12V DC adapter, with an electronic bike lock managing power distribution to components. 
The system operates in two primary modes: 
### Authorized Access Mode: 
  If the fingerprint matches a stored template (IDs 1–5), the ignition is enabled, and the vehicle starts. 
### Unauthorized Access Mode: 
  If the fingerprint is unrecognized, an SMS alert is sent to the owner, the buzzer sounds, and the system waits for the owner’s response to either grant or deny access. 
- Additional features, such as a 400kV voltage booster for a shock mechanism (simulated for safety) and live tracking via hardcoded GPS coordinates, enhance security and recovery capabilities. The modular design ensures scalability and ease of troubleshooting. 
  
## CRICUIT DIGRAM
  <a href="https://github.com/Saieswar439/Vehicle-antitheft-system/blob/main/Screenshot%202025-08-22%20092547.png" a> cricuit image

## 📂 Project Files
- `code/` →<a href= "https://github.com/Saieswar439/Vehicle-antitheft-system/blob/main/project%20code.txt1.txt" a> project code
- `docs/Project →<a href= "https://github.com/Saieswar439/Vehicle-antitheft-system/blob/main/fingerprint%5ELJ_gsm_ignition_document%5B1%5D--_paper%5B1%5D.pdf" a> project_report
- `images/`<a href= "https://github.com/Saieswar439/Vehicle-antitheft-system/blob/main/Vehicle%20Anti(1).pdf" a> FlowDigram

## CONCLUSION  

The Fingerprint-Based Vehicle Anti-Theft System with SMS and Live Tracking was designed to enhance vehicle security by everaging biometric authentication, GSM based remote control, and GPS tracking, tailored specifically for two-wheelers. The project was driven by the need to address the limitations of traditional security systems—such as mechanical locks and basic alarms—which are easily bypassed by modern theft techniques like key duplication and hot-wiring. By integrating fingerprint recognition, SMS communication, and location tracking, the system aimed to provide a multi-layered defense against theft, empowering owners with real time oversight and response capabilities. The project successfully met most of its objectives, including biometric authentication, SMS control, user feedback, ignition control, and cost-effectiveness (total cost ~$50–60). However, the failure to integrate real-time GPS tracking and the system’s dependency on network connectivity highlight areas for improvement. The prototype serves as a proof-ofconcept, demonstrating the potential of low-cost, smart security systems for two-wheelers, while its modular design and open-source platform (Arduino) make it a valuable educational tool for students and researchers in embedded systems and IoT. 
