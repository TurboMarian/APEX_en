

# APEX

## Device Features

- 8 outputs for fuel injectors
- 8 outputs for active ignition coils
- 8 universal AUX outputs
- 4 frequency inputs for VR/HALL sensors
- 12 universal analog inputs (0-5V) (Inputs 1-4 can be used for temperature measurement with a 2.49 kΩ pull-up resistor (SW10 switch)).
- 2 EGT inputs (K-type thermocouples)
- 2 knock sensor inputs
- 8 digital inputs (e.g., HALL-type position sensors, switches, speed sensors, flex fuel, additional camshaft position sensors, etc.)
- 2 H-BRIDGE outputs (6A) (support for two electronic throttle bodies, electronic wastegate valves)
- 2 wideband oxygen sensor controllers LSU 4.9
- 2 Canbus
- Built-in 400kPa pressure sensor
- Built-in barometric pressure sensor
- Built-in microSD card slot (logging over 100 device operation parameters)
- Bluetooth and WiFi

<div align="center">
  <img src="https://github.com/user-attachments/assets/0a5988aa-83cb-4ae6-aedd-f59653917f09" alt="sticker" width="55%">
</div>

## Firmware

## RUSEFI Firmware
(Right click and 'Save link as...')

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20Firmware-blue?style=for-the-badge&logo=download&logoColor=white "Download RusEFI Firmware")]()
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20TunerStudio%20INI-green?style=for-the-badge&logo=download&logoColor=white "Download RusEFI TunerStudio INI")]()
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20Console-purple?style=for-the-badge&logo=download&logoColor=white "Download RusEFI Console")]()
<!-- END LATEST DOWNLOAD BUTTON -->

## FOME Firmware
(Right click and 'Save link as...')

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-FOME%20Firmware-blue?style=for-the-badge&logo=download&logoColor=white "Download FOME Firmware")]()
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-FOME%20TunerStudio%20INI-green?style=for-the-badge&logo=download&logoColor=white "Download FOME TunerStudio INI")]()
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-FOME%20Console-purple?style=for-the-badge&logo=download&logoColor=white "Download FOME Console")]()
<!-- END LATEST DOWNLOAD BUTTON -->

### PINOUT

<div align="center">
<a href="https://opelpanfan.github.io/OPF_ECU/core48_21.html" target="_blank">
  <img src="https://github.com/user-attachments/assets/0e97f710-793b-4ef5-b470-bfc47e76c5db" alt="black" width="100%" />
</a>
</div>

| Pin Number (Gray) | STM32 | Function | | Pin Number (Black) | STM32 | Function |
| --- | --- | --- | --- | --- | --- | --- |
| A1 | | INJECTOR 1 | | D1 | | DIGITAL INPUT 1 |
| A2 | | INJECTOR 2 | | D2 | | CAN 1 L |
| A3 | | INJECTOR 3 | | D3 | | CAN 1 H |
| A4 | | INJECTOR 4 | | D4 | | VR1+/HALL |
| A5 | | INJECTOR 5 | | D5 | | VR1- |
| A6 | | INJECTOR 6 | | D6 | | VR2+/HALL |
| A7 | | INJECTOR 7 | | D7 | | VR2- |
| A8 | | INJECTOR 8 | | D8 | | +12V POWER |
| B1 | | AUX OUTPUT 1 (5A) | | E1 | | H-BRIDGE 2 - |
| B2 | | AUX OUTPUT 2 (5A) | | E2 | | H-BRIDGE 2 + |
| B3 | | AUX OUTPUT 3 (5A) | | E3 | | DIGITAL INPUT 2 |
| B4 | | AUX OUTPUT 4 (5A) | | E4 | | CAN 2 L |
| B5 | | AUX OUTPUT 5 (5A) | | E5 | | CAN 2 H |
| B6 | | AUX OUTPUT 6 (5A) | | E6 | | ANALOG INPUT 1 (0-5V) |
| B7 | | H-BRIDGE 1 - | | E7 | | ANALOG INPUT 2 (0-5V) |
| B8 | | H-BRIDGE 1 + | | E8 | | +5V SENSOR POWER |
| C1 | | COIL 1 | | F1 | | ANALOG INPUT 3 (0-5V) |
| C2 | | COIL 2 | | F2 | | ANALOG INPUT 4 (0-5V) |
| C3 | | COIL 3 | | F3 | | ANALOG INPUT 5 (0-5V) |
| C4 | | COIL 4 | | F4 | | ANALOG INPUT 6 (0-5V) |
| C5 | | COIL 5 | | F5 | | ANALOG INPUT 7 (0-5V) |
| C6 | | COIL 6 | | F6 | | ANALOG INPUT 8 (0-5V) |
| C7 | | COIL 7 | | F7 | | ANALOG INPUT 9 (0-5V) |
| C8 | | COIL 8 | | F8 | | GND |

<div align="center">
  <img src="https://github.com/user-attachments/assets/754b5384-3ff9-43f3-93fb-265ce7787895" alt="sticker" width="50%">
</div>

## PCB Layout

<div align="center">
  <img src="https://github.com/user-attachments/assets/073cc388-bc1d-4599-940b-7406b2930105" alt="sticker" width="95%">
</div>
