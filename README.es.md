# Portafolio de Hardware PCB

**Diseño PCB · Hardware Embebido · Potencia e Interfaces · Integración HW/FW**

Índice visual y compacto de diseños PCB de **Luis Alejandro Pérez Sousa**.

[English](README.md) · [GitHub](https://github.com/alx-sousa)

---

## Diseños PCB

<table>
<tr>
<td width="28%" align="center" valign="top">
  <a href="https://github.com/alx-sousa/P1-Refrigeration-Monitor">
    <img src="https://raw.githubusercontent.com/alx-sousa/P1-Refrigeration-Monitor/main/docs/images/p1_revB_fusion_hero_iso.png" width="250" alt="Integración Fusion del monitor de refrigeración comercial P1 Rev B">
  </a>
</td>
<td width="72%" valign="top">

### [P1 Rev B — Monitor de Refrigeración Comercial](https://github.com/alx-sousa/P1-Refrigeration-Monitor)

Plataforma compacta de monitorización embebida con **PCB de cuatro capas**, desarrollada para un piloto real de refrigeración comercial e integrada alrededor de **ESP32-C6**, carga/power-path LiPo, regulación buck-boost, sonda de temperatura externa, sensor Hall de puerta, RTC, TFT local, buzzer y USB nativo para servicio/programación.

**Enfoque:** arquitectura de hardware orientada a producto, gestión de energía, sensado/interfaces, PCB de cuatro capas, placement consciente de RF, integración mecánica y validación estructurada previa a fabricación.

[Proyecto completo](https://github.com/alx-sousa/P1-Refrigeration-Monitor) · [Arquitectura](https://github.com/alx-sousa/P1-Refrigeration-Monitor/blob/main/docs/architecture.md) · [Plan de validación](https://github.com/alx-sousa/P1-Refrigeration-Monitor/blob/main/docs/validation-plan.md)

**Estado:** hito de diseño PCB Rev B completado · Pre-fabricación

</td>
</tr>
</table>

<table>
<tr>
<td width="28%" align="center" valign="top">
  <a href="https://github.com/alx-sousa/Autonomous-IoT-Monitoring">
    <img src="https://raw.githubusercontent.com/alx-sousa/Autonomous-IoT-Monitoring/main/docs/images/rev2/rev2-final-enclosure-cad.png" width="250" alt="Ensamble Fusion 360 de Autonomous IoT Monitoring REV 2.0">
  </a>
</td>
<td width="72%" valign="top">

### [Autonomous IoT Monitoring — REV 2.0](https://github.com/alx-sousa/Autonomous-IoT-Monitoring)

PCB carrier de dos capas para receptor, con **XIAO ESP32-S3 removible**, interfaz externa para **PN532 RFID**, indicadores locales e integración de batería.

El proyecto completo también incluye un **sistema V1 construido, evaluado y entregado**, con snapshots históricos de firmware sanitizado y limitaciones de prueba documentadas públicamente.

**Enfoque:** sistemas embebidos inalámbricos, hardware modular, integración HW/FW, validación funcional, mantenibilidad y CAD de carcasa.

[Detalles PCB / hardware](https://github.com/alx-sousa/Autonomous-IoT-Monitoring/blob/main/docs/hardware-rev2.md) · [Evaluación V1](https://github.com/alx-sousa/Autonomous-IoT-Monitoring/blob/main/docs/testing.md) · [Estado de validación](https://github.com/alx-sousa/Autonomous-IoT-Monitoring/blob/main/docs/validation.md)

**Estado:** V1 entregada/evaluada · CAD mecánico REV 2.0 completo · REV 2.0 pre-fabricación

</td>
</tr>
</table>

<table>
<tr>
<td width="28%" align="center" valign="top">
  <a href="https://github.com/alx-sousa/DC-Motor-Controller-Encoder">
    <img src="https://raw.githubusercontent.com/alx-sousa/DC-Motor-Controller-Encoder/main/docs/images/rev-a/pcb-3d-perspective.png" width="250" alt="PCB DC Motor Controller with Encoder REV A">
  </a>
</td>
<td width="72%" valign="top">

### [DC Motor Controller with Encoder — REV A](https://github.com/alx-sousa/DC-Motor-Controller-Encoder)

Controlador de **motor DC de 12 V** de dos capas, diseñado a nivel de componente con entrada protegida, etapa buck **TPS54302**, driver **DRV8871**, interfaz de encoder incremental y control mediante **ESP32-C6** removible.

**Enfoque:** selección de componentes, electrónica de potencia, layout del driver, grounding, diseño térmico y planificación estructurada de bring-up.

[Proyecto completo](https://github.com/alx-sousa/DC-Motor-Controller-Encoder) · [Layout PCB](https://github.com/alx-sousa/DC-Motor-Controller-Encoder/blob/main/docs/images/rev-a/pcb-layout-2d.png) · [Ensamble Fusion 360](https://github.com/alx-sousa/DC-Motor-Controller-Encoder/blob/main/docs/images/rev-a/fusion360-system-assembly.png)

**Estado:** diseño REV A completo · DRC aprobado · Pre-fabricación

</td>
</tr>
</table>

---

El orden refleja la fuerza actual del portafolio: **P1 Rev B** lidera por tener la arquitectura PCB más avanzada y orientada a producto, **Autonomous IoT Monitoring** aporta evidencia de un sistema realmente construido/evaluado, y **DC Motor Controller** queda como evidencia complementaria de diseño de potencia y control de motor.

La documentación completa permanece dentro del repositorio propio de cada proyecto.

**Luis Alejandro Pérez Sousa**  
Ingeniería Mecatrónica · Sistemas Embebidos · Electrónica · Diseño PCB · Integración Hardware/Firmware
