# LAN9252 EtherCAT SPI Evaluation Board

<div align="center">

![EtherCAT](https://img.shields.io/badge/Protocol-EtherCAT-blue?style=for-the-badge)
![LAN9252](https://img.shields.io/badge/Controller-LAN9252-green?style=for-the-badge)
![PCB Design](https://img.shields.io/badge/Hardware-PCB%20Design-orange?style=for-the-badge)
![Embedded Systems](https://img.shields.io/badge/Domain-Embedded%20Systems-darkgreen?style=for-the-badge)
![EasyEDA](https://img.shields.io/badge/EDA-EasyEDA-red?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

### Professional EtherCAT Slave Evaluation Board PCB Design

Industrial EtherCAT evaluation board designed using the Microchip LAN9252 EtherCAT controller with SPI interface support.

</div>

---

# 📌 Overview

This repository contains the complete PCB design files and hardware documentation for a custom EtherCAT Slave Evaluation Board based on the **Microchip LAN9252 EtherCAT Controller**.

The project was designed for:
- Embedded Systems Development
- Industrial Communication Learning
- EtherCAT Protocol Exploration
- PCB Design Practice
- Hardware Prototyping
- Educational & Research Purposes

The repository includes:
- PCB design files
- Gerber files
- PCB layout files
- Bill of Materials (BOM)
- 3D PCB renders
- Hardware documentation

---

# ✨ Features

- LAN9252 EtherCAT Controller
- SPI Communication Interface
- Multi-Layer PCB Design
- RJ45 Ethernet Connectivity
- Optimized PCB Routing
- EasyEDA PCB Design
- PCB 3D Visualization
- Embedded Hardware Development

---

# ⚙️ Hardware Specifications

| Parameter | Specification |
|---|---|
| Main Controller | Microchip LAN9252 |
| Communication Protocol | EtherCAT |
| Host Interface | SPI |
| PCB Design Tool | EasyEDA |
| PCB Type | Multi-Layer PCB |
| Ethernet Interface | RJ45 |
| Regulated Voltage | 3.3V |
| Input Voltage | 5V / 12V |
| Project Type | PCB Design Project |
| License | MIT |

---

# 📸 PCB Preview

## 3D Front View

<p align="center">
  <img src="pcb_3d_front.png" alt="LAN9252 EtherCAT PCB 3D Front View" width="900">
</p>

---

## PCB Top View

<p align="center">
  <img src="pcb_top_view.png" alt="LAN9252 EtherCAT PCB Top View" width="900">
</p>

---

## PCB Bottom View

<p align="center">
  <img src="pcb_bottom_view.png" alt="LAN9252 EtherCAT PCB Bottom View" width="900">
</p>

---

## Bottom Layer Routing

<p align="center">
  <img src="pcb_bottom_routing.png" alt="LAN9252 EtherCAT PCB Bottom Routing" width="900">
</p>

---

## PCB Layout

<p align="center">
  <img src="pcb_layout.png" alt="LAN9252 EtherCAT PCB Layout" width="900">
</p>

---

# 📂 Repository Structure

```text
LAN9252-EtherCAT-SPI-EVB/
│
├── README.md
├── LICENSE
│
├── pcb_3d_front.png
├── pcb_top_view.png
├── pcb_bottom_view.png
├── pcb_bottom_routing.png
├── pcb_layout.png
│
├── gerber/
│   └── LAN9252_EtherCAT_Gerber_v1.0.zip
│
├── schematic/
│   └── LAN9252_Schematic.pdf
│
├── pcb_layout/
│   └── PCB_Layout.pdf
│
├── bom/
│   └── BOM_LAN9252.csv
│
└── docs/
    └── DESIGN_GUIDE.md
```

---

# 🧠 System Architecture

```text
┌──────────────────────────────────┐
│        LAN9252 Controller        │
│      EtherCAT Slave Device       │
└──────────────┬───────────────────┘
               │
      ┌────────┴────────┐
      │                 │
┌────────────┐   ┌────────────┐
│ Ethernet   │   │ SPI Host   │
│ Interface  │   │ Interface  │
└────────────┘   └────────────┘
       │                 │
    RJ45 Port       External MCU
```

---

# 📦 Included Files

## PCB Design Files
- Gerber Files
- Drill Files
- PCB Layout Files

## Documentation
- PCB Layout PDF
- Bill of Materials (CSV)
- Design Documentation

## Visualization
- PCB 3D Renders
- PCB Layout Images

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/AxayRam/LAN9252-EtherCAT-SPI-EVB.git
```

---

# 🔌 Hardware Integration

- Connect external MCU through SPI interface
- Connect Ethernet cable to RJ45 connector
- Use appropriate power supply
- Configure EtherCAT firmware stack
- Test communication using EtherCAT master tools

---

# 🌐 EtherCAT Technology

EtherCAT (Ethernet for Control Automation Technology) is a real-time industrial Ethernet communication protocol widely used in industrial automation and embedded systems.

## Advantages

- Real-Time Communication
- Low Latency
- Deterministic Performance
- Industrial Reliability
- High-Speed Data Transfer

---

# 🛠️ PCB Design Highlights

## Signal Routing
- Optimized routing structure
- Organized component placement
- Differential signal considerations

## Power Design
- Stable voltage regulation
- Decoupling capacitor placement
- Power filtering network

## PCB Engineering
- Multi-layer PCB architecture
- Ground plane optimization
- Compact hardware layout

---

# 📋 Main Components

- LAN9252 EtherCAT Controller
- RJ45 Ethernet Connector
- SPI Interface Header
- Crystal Oscillator
- Voltage Regulation Circuit
- Passive Components
- Protection Components

---

# 📖 Documentation

| File | Description |
|---|---|
| README.md | Project Overview |
| DESIGN_GUIDE.md | Hardware Design Notes |
| LICENSE | MIT License |

---

# 📜 License

This project is licensed under the MIT License.

You are free to:
- Use commercially
- Modify the design
- Share the files
- Use for educational purposes

Please include the original license and copyright notice.

---

# 👨‍💻 Author

### Axay Ram

Embedded Systems | PCB Design | Industrial Communication | EtherCAT Development

---

# ⭐ Support

If you found this project useful:
- Star the repository
- Fork the project
- Share with others

---

# 📅 Project Information

| Item | Value |
|---|---|
| Project | LAN9252 EtherCAT SPI EVB |
| PCB Tool | EasyEDA |
| Project Type | PCB Design |
| Version | v1.0 |
| Last Updated | April 2026 |

---

<div align="center">

### Embedded Hardware & PCB Design Project

EtherCAT Evaluation Board using Microchip LAN9252

</div>
