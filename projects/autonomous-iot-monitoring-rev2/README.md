# Autonomous IoT Monitoring — REV 2.0

**Custom receiver PCB · XIAO ESP32-S3 · PN532 · Fusion 360**

[Full system repository](https://github.com/alx-sousa/Autonomous-IoT-Monitoring)

---

## Visuals

<p align="center">
  <img src="../../assets/projects/autonomous-iot-monitoring-rev2/fusion360-rev2-assembly.png" width="72%" alt="Autonomous IoT Monitoring REV 2.0 assembly in Fusion 360">
</p>

<p align="center"><em>Fusion 360 mechanical assembly — removable XIAO ESP32-S3 and external PN532 integration.</em></p>

<p align="center">
  <img src="../../assets/projects/autonomous-iot-monitoring-rev2/easyeda-rev2-pcb.png" width="58%" alt="Autonomous IoT Monitoring REV 2.0 PCB in EasyEDA Pro">
</p>

<p align="center"><em>REV 2.0 PCB design in EasyEDA Pro before fabrication.</em></p>

## Overview

REV 2.0 evolves the receiver from prototype-level wiring into a cleaner, maintainable two-layer carrier PCB.

The design keeps the **XIAO ESP32-S3** and **PN532** removable instead of permanently soldered, improving serviceability, reuse and development access.

## Key decisions

- [Removable XIAO ESP32-S3](#removable-xiao-esp32-s3)
- [Removable PN532 interface](#removable-pn532-interface)
- [Fusion 360 mechanical integration](#fusion-360-mechanical-integration)
- [Current engineering status](#current-engineering-status)

### Removable XIAO ESP32-S3

Female headers keep the controller replaceable and reusable while preserving firmware/debug access. Mechanical integration is also being used to maintain USB-C accessibility and antenna clearance.

### Removable PN532 interface

The RFID module remains external through a four-contact interface so it can be replaced or repositioned independently from the carrier PCB.

### Fusion 360 mechanical integration

The PCB is being assembled in Fusion 360 with 3D reference models to review:

- enclosure fit;
- module and connector access;
- antenna clearance;
- component height;
- OLED, buzzer and RFID placement;
- serviceability before fabrication.

Reference CAD is used for spatial review only. Critical dimensions still require manufacturer-document verification and later physical fit testing.

## Current engineering status

| Stage | Status |
|---|---|
| Schematic | Complete |
| PCB layout | Complete |
| DRC | Passed |
| Fusion 360 assembly | In progress |
| Enclosure CAD | In progress |
| Fabrication | Pending |
| Bring-up | Pending |
| Physical validation | Pending |

## Tools

EasyEDA Pro · Fusion 360 · XIAO ESP32-S3 · PN532 · I²C · GPIO

---

**Note:** CAD completion is not presented as physical validation. Fabrication, fit checks and electrical bring-up remain pending.
