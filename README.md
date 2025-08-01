# TEMPERATURE-MONITORING-SYSTEM
# TEMPERATURE MONITORING SYSTEM USING LM35 SENSOR

**COMPANY**: CODTECH IT SOLUTIONS
**NAME**: OMKAR GURAV
**INTERN ID**: CT04DG2476
**DOMAIN**: Embedded Systems
**DURATION**: 4 WEEKS
**MENTOR**: NEELA SANTOSH


##  Project Overview

This project demonstrates a temperature monitoring system built using the **LM35 analog temperature sensor**, **Arduino Uno**, and a **16x2 LCD display**. It was developed during a 4-week internship at **CODTECH IT SOLUTIONS** as part of an exploration into analog signal processing and real-time sensor data display in embedded systems.

The setup reads temperature data from the LM35 sensor, converts it into Celsius using analog-to-digital conversion (ADC), and displays it on the LCD in real time. This kind of system is widely used in climate control, weather stations, and home automation.


## Objectives

* Understand how to interface an analog temperature sensor with a microcontroller.
* Learn how to use the ADC of Arduino for real-time sensor input.
* Display sensor readings on an LCD screen using Embedded C.
* Simulate the project using Proteus before actual implementation.



##  Tools & Components

* **IDE**: Arduino IDE
* **Simulation Software**: Proteus Design Suite
* **Language**: Embedded C
* **Hardware Components**:

  * Arduino Uno
  * LM35 Temperature Sensor
  * 16x2 LCD Display (LM016L)
  * Potentiometer (for contrast adjustment)
  * Jumper wires and breadboard (in practical setup)

## How It Works

1. The LM35 outputs an analog voltage proportional to the temperature (10mV/°C).
2. Arduino reads this voltage through one of its analog pins (A0).
3. The analog reading is converted to Celsius using a formula in code.
4. The temperature value is displayed on the LCD using standard library functions.



## Output Image


