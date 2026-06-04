# Industrial SCADA Interface Using ESP32


**Project Title:** Industrial SCADA Interface Using ESP32

**Intern Name:** __Jenifer J__

**Intern ID:**__________CITS2086__________


---

## Project Overview

The Industrial SCADA Interface is a real-time monitoring and control system developed using the ESP32 microcontroller. The system continuously monitors water level, temperature, and humidity using sensors and provides status indications through LEDs, a relay module, and a buzzer.

The project demonstrates industrial automation concepts including data acquisition, process monitoring, alert generation, and actuator control.

---

## Features

* Real-time Water Level Monitoring
* Temperature Monitoring
* Humidity Monitoring
* Tank Low Detection
* High Temperature Alert
* Relay-Based Control
* Visual Status Indication Using LEDs
* Audible Alert Using Buzzer
* Industrial SCADA Style Monitoring

---

## Hardware Components

| Component                 | Quantity    |
| ------------------------- | ----------- |
| ESP32 Development Board   | 1           |
| DHT22 Sensor              | 1           |
| HC-SR04 Ultrasonic Sensor | 1           |
| Relay Module              | 1           |
| Buzzer                    | 1           |
| Red LED                   | 1           |
| Green LED                 | 1           |
| Breadboard                | 1           |
| Jumper Wires              | As Required |

---

## Software Requirements

* Wokwi Simulator
* Arduino IDE
* ESP32 Board Package
* DHT Sensor Library

---

## Project Workflow

1. Read Water Level using HC-SR04.
2. Read Temperature and Humidity using DHT22.
3. Process sensor data using ESP32.
4. Compare values with predefined thresholds.
5. Generate status messages.
6. Activate LEDs, Relay, and Buzzer.
7. Display results on Serial Monitor.

---

## Output Conditions

### Tank Low Condition

* Water Level < 30%
* Green LED ON
* Relay ON
* Buzzer OFF

### Normal Condition

* Water Level between 30% and 70%
* Green LED ON
* Relay OFF
* Buzzer OFF

### High Temperature Condition

* Temperature > 35°C
* Red LED ON
* Buzzer ON
* Relay OFF

---

## Results

The system successfully detected:

* Tank Low Condition
* Normal Operating Condition
* High Temperature Alert Condition

Real-time sensor values were displayed on the Serial Monitor and corresponding outputs were activated automatically.

---

## Applications

* Industrial Water Tank Monitoring
* Process Automation
* Smart Factories
* Environmental Monitoring
* Industrial Safety Systems
* SCADA-Based Monitoring Systems

---

## Future Enhancements

* Cloud Dashboard Integration
* Mobile App Notifications
* Data Logging
* MQTT Communication
* Predictive Maintenance using AI
* Web-Based Monitoring Interface

---

## Conclusion

The Industrial SCADA Interface using ESP32 successfully demonstrates industrial monitoring and automation concepts through real-time acquisition of water level, temperature, and humidity data. The system provides reliable status indications and can be expanded into a complete IoT-based SCADA solution.

---


