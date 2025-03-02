

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
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20Firmware-blue?style=for-the-badge&logo=download&logoColor=white "Download RusEFI Firmware")](https://github.com/user-attachments/files/19044275/rusefi.zip)
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20TunerStudio%20INI-green?style=for-the-badge&logo=download&logoColor=white "Download RusEFI TunerStudio INI")](https://github.com/user-attachments/files/19044270/rusefi_apex.zip)
<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-RusEFI%20Console-purple?style=for-the-badge&logo=download&logoColor=white "Download RusEFI Console")](https://drive.google.com/file/d/1GC37ijTprq1gyn9G_KEFeLXi3cPBaATD/view?usp=drive_link)
<!-- END LATEST DOWNLOAD BUTTON -->

## FOME Firmware
(Right click and 'Save link as...')

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-FOME%20Firmware-blue?style=for-the-badge&logo=download&logoColor=white "Pobierz FOME Firmware")](https://github.com/user-attachments/files/19044513/fome.zip)

<!-- END LATEST DOWNLOAD BUTTON -->

<!-- BEGIN LATEST DOWNLOAD BUTTON -->
[![Download zip](https://custom-icon-badges.demolab.com/badge/-FOME%20TunerStudio%20INI-green?style=for-the-badge&logo=download&logoColor=white "Download FOME TunerStudio INI")](https://github.com/user-attachments/files/19044515/fome_apex.zip)

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

## PCB Layout

<div align="center">
  <img src="https://github.com/user-attachments/assets/6b73b7d4-867f-4398-a5b6-4b52e0a0de97" alt="naklejka" width="100%">
</div>

## WIDEBAND PINOUT

<table>
  <tr>
    <td>
      <div align="left">
        <img src="https://github.com/user-attachments/assets/b496d4ea-cc52-464d-8e90-a2e83be1d03b" alt="naklejka" width="70%">
      </div>
    </td>
    <td align="center">
      <strong>WIDEBAND 1:</strong><br><br>
      1 - LSU PIN 4<br>
      2 - LSU PIN 6<br>
      3 - LSU PIN 2<br>
      4 - LSU PIN 5<br>
      5 - LSU PIN 1<br>
      <br><strong>LSU PIN 3 - CONNECT TO SWITCHED +12V WITH 5A FUSE</strong>
    </td>
    <td align="center">
      <strong>WIDEBAND 2:</strong><br><br>
      1 - LSU PIN 4<br>
      2 - LSU PIN 6<br>
      3 - LSU PIN 2<br>
      4 - LSU PIN 5<br>
      5 - LSU PIN 1<br>
      <br><strong>LSU PIN 3 - CONNECT TO SWITCHED +12V WITH 5A FUSE</strong>
    </td>
  </tr>
</table>

## LSU 4.9 CONNECTOR

<div align="left">
        <img src="https://github.com/user-attachments/assets/5913830f-605d-4a51-9635-8c93a41e3664" alt="naklejka" width="55%">
      </div>

## EGT/ANALOG/KNOCK/USB/DIGITAL/AUX CONNECTORS

<table>
  <tr>
    <td>
      <div align="left">
        <img src="https://github.com/user-attachments/assets/8e5822b1-3525-4df8-8b20-5a3d4dfbc909" alt="VR" width="105%">
      </div>
    </td>
    <td align="center">
      <strong>EGT:</strong><br><br>
      1 - K+<br>
      2 - K-<br>
      3 - K1+<br>
      4 - K1-
    </td>
    <td align="center">
      <strong>ANALOG IN:</strong><br><br>
      1 - ANALOG INPUT 10<br>
      2 - ANALOG INPUT 11<br>
      3 - ANALOG INPUT 12<br>
      4 - NOT USED
    </td>
    <td align="center">
      <strong>KNOCK:</strong><br><br>
      1 - KNOCK SENSOR 1<br>
      2 - KNOCK SENSOR 2<br>
      3 - KNOCK AUDIO OUTPUT 1<br>
      4 - KNOCK AUDIO OUTPUT 2
    </td>
    <td align="center">
      <strong>USB:</strong><br><br>
      1 - VBUS<br>
      2 - D-<br>
      3 - D+<br>
      4 - GND
    </td>
    <td align="center">
      <strong>DIGITAL IN:</strong><br><br>
      1 - DIGITAL IN 3<br>
      2 - DIGITAL IN 4<br>
      3 - DIGITAL IN 5<br>
      4 - DIGITAL IN 6
    </td>
    <td align="center">
      <strong>DIGITAL IN/AUX:</strong><br><br>
      1 - DIGITAL IN 7<br>
      2 - DIGITAL IN 8<br>
      3 - AUX 7<br>
      4 - AUX 8
    </td>
  </tr>
</table>



<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h2>SPI5 CONNECTOR & VR INPUTS CONNECTOR</h2>

<table>
  <tr>
    <!-- SPI5 -->
    <td>
      <img src="https://github.com/user-attachments/assets/ea6489d2-817d-4648-8d05-b27e5785b4d7" alt="SPI5" width="40%">
    </td>
    <td class="desc">
      <strong>SPI5:</strong><br><br>
      1 - SPI5 SCK<br>
      2 - SPI5 MISO<br>
      3 - SPI5 MOSI<br>
      4 - SPI5 CS1 (PF10)<br>
      5 - SPI5 CS2 (PF5)
    </td>
  </tr>
  <tr>
    <!-- VR -->
    <td>
      <img src="https://github.com/user-attachments/assets/9d346c36-0cd5-4926-82a2-080b6bc4a592" alt="VR" width="40%">
    </td>
    <td class="desc">
      <strong>VR:</strong><br><br>
      1 - VR3-<br>
      2 - VR3+<br>
      3 - VR4-<br>
      4 - VR4+
    </td>
  </tr>
</table>


## OBUDOWA
<div align="center">
  <img src="https://github.com/user-attachments/assets/754b5384-3ff9-43f3-93fb-265ce7787895" alt="naklejka" width="55%">
</div>

## PCB
<div align="center">
  <img src="https://github.com/user-attachments/assets/4fd3904c-2e51-4152-aae9-a1798210707b" alt="pcb" width="55%">
</div>
