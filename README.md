# 📡 Night Ride – Si468x Module

Open-source DAB/FM receiver module based on the **Silicon Labs / Skyworks Si468x series**.

This project provides hardware, software, and documentation to integrate a modern digital radio receiver into automotive and embedded Linux systems.

---

## Overview

The Si468x is a highly integrated broadcast receiver supporting:

- **DAB / DAB+**
- **FM (RDS)**
- Digital audio output via **I2S**
- Control via **SPI / I2C**

This repository focuses on building an **open and reusable platform** around the chip.

---

## Features

- Custom **M.2 E-Key module** design
- Automotive-oriented integration (infotainment systems)
- Linux driver / userspace control (WIP)
- Modular and reusable hardware design

---

## Repository Structure

```
/pcb        → KiCad schematics & PCB layouts
/driver     → Linux driver / interface code (WIP)
/tools      → debugging and testing utilities
/firmware   → placeholder (not included, see below)
```

---

## ⚠️ Firmware Notice

The Si468x requires proprietary firmware provided by the vendor.

❌ Firmware is **NOT included** in this repository  
❌ Redistribution is **not permitted**

See [`/firmware/README.md`](firmware/README.md) for details on how to obtain and use firmware.

---

## Hardware

Planned / current design goals:

- Si4689-based RF frontend
- M.2 E-Key form factor
- External antenna support
- I2S digital audio output
- SPI / I2C host interface

---

## Software

Planned features:

- Linux integration (userspace or kernel driver)
- Station tuning and service selection
- DAB / FM metadata parsing
- Integration into infotainment systems

---

## Documentation

Due to licensing restrictions, some vendor documentation is not included.

You may need to obtain:
- Programming guides
- Firmware files
- Additional application notes

These are typically available via:
- Community forums
- Existing development kits

---

## Status

🚧 Work in progress

- PCB: in development
- Driver: pending
- Testing: pending

---

## Licensing

This repository contains multiple components under different licenses:

- **Software (`/driver`, `/tools`)**  
  Licensed under the GNU General Public License v3.0 (GPL-3.0)

- **Hardware (`/pcb`)**  
  Licensed under the CERN Open Hardware License v2 – Strongly Reciprocal (CERN-OHL-S-2.0)

- **Firmware**  
  Not included. Proprietary and subject to vendor licensing.

See the individual folders for more details.

---

## 🌙 Night Ride

Part of the Night Ride open-source automotive platform.
