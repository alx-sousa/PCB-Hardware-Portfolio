# Portafolio de PCB e Integración de Hardware

**Diseño PCB · Hardware Embebido · Integración Mecánica · DFM · Bring-Up**

Portafolio técnico de **Luis Alejandro Pérez Sousa**, enfocado en diseño de PCB e integración hardware–firmware para sistemas embebidos e IoT.

[English version](README.md)

---

## Proyecto actual destacado

### Autonomous IoT Monitoring — REV 2.0

PCB personalizada de dos capas desarrollada como evolución de hardware de un prototipo funcional de monitoreo hospitalario.

<p align="center">
  <img src="assets/projects/autonomous-iot-monitoring-rev2/easyeda-rev2-pcb.png" width="43%" alt="PCB Autonomous IoT Monitoring REV 2.0 en EasyEDA Pro">
  &nbsp;&nbsp;
  <img src="assets/projects/autonomous-iot-monitoring-rev2/fusion360-rev2-assembly.png" width="52%" alt="Ensamble mecánico Autonomous IoT Monitoring REV 2.0 en Fusion 360">
</p>

La placa se completó y revisó primero en **EasyEDA Pro** y después pasó a **Fusion 360** para evaluar la PCB como parte del sistema mecánico completo y no como una placa aislada.

Decisiones principales:

- **XIAO ESP32-S3 removible** mediante headers hembra en lugar de soldadura permanente.
- **PN532 RFID externo y removible** mediante una interfaz de cuatro contactos.
- Acceso al USB-C y despeje de antena considerados durante la integración mecánica.
- Revisión de alturas, posición de OLED/buzzer y holguras con la carcasa antes de fabricar.
- Los modelos 3D se consideran referencias mecánicas; las dimensiones críticas todavía deben validarse con datasheets y posteriormente con hardware físico.

**Estado actual:** esquemático y layout terminados, DRC aprobado, integración mecánica en Fusion 360 en proceso y carcasa CAD en desarrollo. Fabricación, validación física de ajuste y bring-up eléctrico siguen pendientes.

[Ver notas de ingeniería →](projects/autonomous-iot-monitoring-rev2/README.md)

---

## Objetivo de este repositorio

Este repositorio está enfocado deliberadamente en **PCB y hardware embebido**, no en modelado 3D general.

Cada proyecto documentará el proceso:

**Requisitos → Esquemático → Verificación de footprints → Placement → Ruteo → DRC → Integración mecánica → DFM → Fabricación → Bring-up → Validación**

### Enfoque técnico

- Placas carrier para sistemas embebidos e IoT
- Diseño y ruteo de PCB de dos capas
- Verificación de componentes y footprints
- Integración de módulos removibles
- Interfaces hardware–firmware
- Integración mecánica en Fusion 360
- DFM y preparación para fabricación
- Documentación de bring-up y validación

## Proyectos

| Proyecto | Herramientas / plataforma | Estado |
|---|---|---|
| [Autonomous IoT Monitoring — REV 2.0](projects/autonomous-iot-monitoring-rev2/README.md) | EasyEDA Pro · Fusion 360 · XIAO ESP32-S3 · PN532 | Integración mecánica / pre-fabricación |

Solo se agregarán nuevos diseños cuando exista suficiente evidencia de ingeniería para documentarlos correctamente.

## Filosofía de diseño

Una PCB no está terminada únicamente porque el ruteo esté completo.

Los footprints críticos se comparan con documentación del fabricante cuando es posible, las restricciones mecánicas se revisan antes de fabricar y la evidencia CAD se mantiene separada de cualquier afirmación de validación física.

El objetivo es mostrar **cómo se diseñó el hardware, por qué se tomaron determinadas decisiones, qué se ha verificado y qué falta probar**.

---

## Autor

**Luis Alejandro Pérez Sousa**  
Ingeniería Mecatrónica · Sistemas Embebidos · IoT · Diseño PCB · Integración Hardware/Firmware

[GitHub](https://github.com/alx-sousa) · [Repositorio completo de Autonomous IoT Monitoring](https://github.com/alx-sousa/Autonomous-IoT-Monitoring)
