# Air Pollution Monitoring with SMS Reporting – KiCad Design

## Overview
This repository contains the **KiCad schematic and PCB design files** for an Air Pollution Monitoring system with SMS reporting. The system is designed to track harmful gases and air quality levels in industrial and urban environments using multiple gas sensors. When pollution exceeds a set threshold, the system triggers alerts through a buzzer and sends **real-time SMS notifications** via the SIM900 GSM module, enabling proactive safety measures.

## Repository Contents
- `/schematics` → KiCad schematic files (.sch)  
- `/pcb` → PCB layout design (.kicad_pcb)  
- `/gerber` → Generated Gerber files for PCB manufacturing  
- `/3d` → 3D board visualization   

## Components in the Design
- **Arduino Uno interface** (MCU connections)  
- **MQ135 Gas Sensors (x2)** – Detect CO₂, NH₃, Benzene, etc.  
- **MQ9 Sensor** – Detects CO and combustible gases  
- **DHT Sensor** – Monitors temperature and humidity  
- **SIM900 GSM Module** – Sends SMS alerts  
- **Buzzer** – Local alert for high pollution levels  
 




