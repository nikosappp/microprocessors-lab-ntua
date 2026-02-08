# AVR Lab Exercises – ATmega328PB 

Solutions for the 7th‑semester Microprocessors Lab course at the National Technical University of Athens (2025–26).


This repository contains codes for a series of AVR microcontroller lab applications using the ATmega328PB on the ntuAboard_G1 platform.

<img width="828" height="592" alt="image" src="https://github.com/user-attachments/assets/b57bd34f-9e6d-458a-8c3b-b69cacd37afb" />

## Contributors
- Nikolaos Apostolopoulos
- Nektarios Vasiliou

### Lab 1: Basic Assembly & Timing
Implemented basic Assembly structure: Stack and I/O initialization. Created delay routines to control timing for various LED patterns.

### Lab 2: External Interrupts & Debouncing
Configured external interrupts (INT0/INT1) to handle button inputs. Applied software debouncing and implemented automated LED control via ISRs in both Assembly and C.

### Lab 3: Timers, PWM & ADC
Generated PWM signals using Timer1 for LED brightness control (PB1). Simultaneously utilized the 10-bit ADC to read sensor data and visualize values on LEDs.

### Lab 4: LCD & CO Sensor
Interfaced a 2x16 LCD to display voltage readings from a potentiometer and a CO sensor. Implemented a threshold-based alert system using LEDs and the LCD.

### Lab 5: TWI (I²C) & PCA9555
Established I²C communication with the PCA9555 I/O expander. Processed logic functions from PORTB inputs and controlled LEDs and the LCD via the expander.

### Lab 6: 4x4 Keypad via I²C
Developed a driver for a 4x4 keypad connected to the PCA9555. Mapped key presses to ASCII and implemented an electronic lock mechanism with a two-digit code.

### Lab: DS1820 Sensor (1-Wire)
Implemented the 1-Wire protocol for the DS18B20 temperature sensor (PD4). Displayed temperature readings on the LCD, supporting signed values and error handling.

### Lab 8: UART & IoT Scenario
Integrated all modules and used UART to communicate with an ESP8266. Created an IoT "Hospital Demo" scenario to transmit vital signs to a server via WiFi.

