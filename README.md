# PCB & Hardware Integration Portfolio

**PCB Design · Embedded Hardware · Mechanical Integration · DFM · Bring-Up**

Engineering portfolio by **Luis Alejandro Pérez Sousa**, focused on PCB design and hardware–firmware integration for embedded and IoT systems.

[Versión en español](README.es.md)

---

## Current highlight

### Autonomous IoT Monitoring — REV 2.0

A custom two-layer receiver PCB developed as the hardware evolution of a functional hospital-monitoring prototype.

<p align="center">
  <img src="assets/projects/autonomous-iot-monitoring-rev2/easyeda-rev2-pcb.png" width="43%" alt="Autonomous IoT Monitoring REV 2.0 PCB in EasyEDA Pro">
  &nbsp;&nbsp;
  <img src="assets/projects/autonomous-iot-monitoring-rev2/fusion360-rev2-assembly.png" width="52%" alt="Autonomous IoT Monitoring REV 2.0 mechanical assembly in Fusion 360">
</p>

The board was first completed and reviewed in **EasyEDA Pro**, then moved into **Fusion 360** to evaluate the PCB as part of the complete mechanical system rather than as an isolated board.

The most important integration decisions are:

- **Removable XIAO ESP32-S3** through female headers instead of permanent soldering.
- **Removable external PN532 RFID module** through a four-contact interface.
- USB-C accessibility and antenna clearance considered during mechanical integration.
- Component height, OLED/buzzer placement and enclosure clearances reviewed before fabrication.
- 3D models treated as mechanical references; critical dimensions still require datasheet and physical verification.

**Current status:** schematic and PCB layout complete, DRC passed, Fusion 360 mechanical integration in progress, enclosure CAD in progress. Fabrication, physical fit validation and electrical bring-up remain pending.

[View the engineering notes →](projects/autonomous-iot-monitoring-rev2/README.md)

---

## What this repository documents

This repository is intentionally focused on **PCB and embedded-hardware engineering**, not general 3D modeling.

Each project is documented around the engineering decisions that matter for real hardware:

**Requirements → Schematic → Footprint verification → Placement → Routing → DRC → Mechanical integration → DFM → Fabrication → Bring-up → Validation**

### Technical focus

- Embedded and IoT carrier boards
- Two-layer PCB design and routing
- Component and footprint verification
- Removable-module integration
- Hardware–firmware interfaces
- Mechanical integration in Fusion 360
- DFM and fabrication preparation
- Bring-up and validation documentation

## Projects

| Project | Tools / platform | Status |
|---|---|---|
| [Autonomous IoT Monitoring — REV 2.0](projects/autonomous-iot-monitoring-rev2/README.md) | EasyEDA Pro · Fusion 360 · XIAO ESP32-S3 · PN532 | Mechanical integration / pre-fabrication |

More designs will be added only when there is enough engineering evidence to document them properly.

## Design philosophy

A PCB is not considered finished because routing is complete.

Critical footprints are checked against manufacturer documentation when possible, mechanical constraints are reviewed before fabrication, and CAD evidence is kept separate from claims of physical validation.

The goal of this repository is to show **how the hardware was designed, why decisions were made, what has been verified, and what still needs testing**.

---

## Author

**Luis Alejandro Pérez Sousa**  
Mechatronics Engineering · Embedded Systems · IoT · PCB Design · Hardware/Firmware Integration

[GitHub profile](https://github.com/alx-sousa) · [Full Autonomous IoT Monitoring repository](https://github.com/alx-sousa/Autonomous-IoT-Monitoring)
