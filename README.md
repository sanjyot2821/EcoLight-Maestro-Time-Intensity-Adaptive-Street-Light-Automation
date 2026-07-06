# EcoLight-Maestro-Time-Intensity-Adaptive-Street-Light-Automation
EcoLight Maestro is an LPC2148-based smart street light automation system that controls LEDs using real-time clock (RTC) scheduling and LDR-based ambient light sensing. Street lights turn ON automatically at night when light intensity is low, improving energy efficiency while providing an easy RTC time-setting interface through keypad and LCD.
## ECOLIGHT MAESTRO – TIME & INTENSITY ADAPTIVE STREET LIGHT AUTOMATION
Overview

EcoLight Maestro is an embedded system project developed using the LPC2148 ARM7 microcontroller. The system automatically controls street lights based on real-time clock scheduling and ambient light intensity. By combining RTC (Real-Time Clock) and LDR (Light Dependent Resistor) sensing, the project ensures efficient energy utilization by switching street lights ON only when required.

## Features

*Automatic street light control
RTC-based time scheduling
LDR-based light intensity monitoring
Energy-efficient operation
Real-time date and time display on LCD
RTC editing through keypad interface
External interrupt-based configuration mode
User-friendly LCD menu system
Embedded C implementation
Hardware Components
LPC2148 ARM7 Microcontroller
16×2 LCD Display
Matrix Keypad
LDR (Light Dependent Resistor)
LEDs (Street Light Simulation)
Buzzer
Push Button Switch (Interrupt)
Power Supply Circuit
Connecting Wires and PCB
Software Used
Embedded C
Keil uVision
Flash Magic

## Working Principle

The system continuously monitors the current time using the on-chip Real-Time Clock (RTC). During the predefined night period (6:00 PM to 6:00 AM), the LPC2148 reads the ambient light intensity through the LDR using the ADC module.

If the light intensity falls below a specified threshold, the street light LEDs are automatically switched ON. Otherwise, they remain OFF. During daytime hours, the system only displays the current date and time on the LCD without activating the lights.

An external interrupt mechanism allows the user to enter RTC configuration mode. Using the keypad, the user can modify time, date, month, year, and day settings. All entered values are validated before updating the RTC registers. After configuration, the system resumes normal automatic street light operation.

## Advantages

Reduces power consumption
Minimizes manual intervention
Improves street lighting efficiency
Supports accurate time-based control
Easy RTC configuration and maintenance
Cost-effective smart lighting solution
Applications
Smart Street Lighting Systems
Residential Colonies
Highways and Roads
Campus Lighting
Industrial Premises
Energy Conservation Projects
## Demo image
<img width="1918" height="1021" alt="Screenshot 2026-07-06 175330" src="https://github.com/user-attachments/assets/a3adb717-f4ce-4dea-8aa5-fac331d7957b" />


## Author

Sanjyot Laxman Dake

BE – Electronics & Telecommunication Engineering

VPKBIET, Baramati
