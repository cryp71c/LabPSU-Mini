# LabPSU-Mini
Modular desktop power supply with selectable voltage rails and microcontroller monitoring

# Desktop PSU Project 🔌🧠

A modular, 3-voltage desktop power supply (9V / 5V / 3.3V) with:
- LM2596 buck converters
- Arduino Nano for temperature monitoring
- Rotary voltage selector
- Active cooling + heatsinks
- 3D printed ABS enclosure

---

## 🔧 Features
- Rotary switch-selectable voltage rails
- Internal fan cooling system
- PD-ready, low profile power input
- All components enclosed in heat-tolerant ABS

---

## 🧱 Build Log
- [ ] Designed Enclosure for electronic components in FreeCad
- [ ] Designed buck converter brackets in FreeCAD
- [ ] Created front panel layout (voltage oled and rotary switch)
- [ ] Add OLED display for voltage/temp readout
- [ ] Mount microcontroller inside

### Initial Baseplate Images

This will eventually have dovetails drawn, and a ventalation hole (the 120mm square hole), ill probably cut it down a lot so the fan can screw in.

![Base Plate Initial](images/initial_base_plate_design.jpg)

---

## 📐 Folder Structure

- `enclosure/` → 3D models (FreeCAD, STL)
- `electronics/` → Schematics (KiCad), PCB layouts
- `firmware/` → Arduino/Pico code
- `images/` → Renders, wiring diagrams, final photos
- `docs/` → Reports, notes, datasheets

---

## 🧾 Licensing
- [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  
  **Code (`firmware/`)** is licensed under the MIT License.

- [![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC--BY--SA%204.0-lightgrey.svg)](LICENSE-CC-BY-SA.txt)  
  **Design files (`enclosure/`, `electronics/`, `images/`)** and documentation are licensed under  
  [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).  
  *LabPSU-Mini © 2025 by Alexander Rapino is licensed under CC BY-SA 4.0.*

Please attribute accordingly and respect the terms when remixing or redistributing.