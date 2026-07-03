# 5V Linear Breadboard Power Supply

## Overview
A stable, heavily filtered 5V DC power supply built on a breadboard, designed to step down a raw 9.6V NiMH battery pack. This module serves as the foundational power grid for all subsequent digital logic and microcontroller projects. 

## Hardware Specifications
* **Input Voltage:** 9.6V DC (8x AA NiMH cells in series)
* **Output Voltage:** 5.0V DC 
* **Core Regulator:** STMicroelectronics L7805CV (with TO-220 aluminum heatsink for thermal dissipation)
* **Reverse Polarity Protection:** 1N4007 Diode on the input rail.
* **Filtering:**
  * Input Buffer: 100µF Electrolytic Capacitor (smooths battery sag)
  * Output Filter: 10µF Electrolytic Capacitor (suppresses logic switching ripple)
* **Status Indicator:** 5mm Red LED driven by a 1kΩ current-limiting resistor.

## Schematic
<img width="616.5" height="270.75" alt="image" src="https://github.com/user-attachments/assets/406a1c7a-dc4d-431c-9c56-dd3be36e2a89" />


## Testing & Verification
* Open-circuit input voltage verified at ~9.6V via digital multimeter.
* Regulated output voltage verified at a stable 5.0V under no-load and light-load conditions.
* Continuity testing performed to ensure complete electrical isolation between the L7805 thermal tab and the aluminum heatsink.

## Breadboard layout

<img width="380" height="512" alt="image" src="https://github.com/user-attachments/assets/98ca3e85-e800-4d55-82ab-3f7d4d6b899d" />


## Schematic and PCB Documentation

I created the schematic using KiCad software. While my schematic has been verified, I have moved the components over to PCB software. PCB layout and component placement is in progress.
