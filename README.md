# LAN9252 EtherCAT SPI Evaluation Board

<div align="center">

![EtherCAT](https://img.shields.io/badge/Protocol-EtherCAT-blue?style=for-the-badge)
![LAN9252](https://img.shields.io/badge/Controller-LAN9252-green?style=for-the-badge)
![PCB Design](https://img.shields.io/badge/Hardware-PCB%20Design-orange?style=for-the-badge)
![Industrial Automation](https://img.shields.io/badge/Application-Industrial%20Automation-darkgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Manufacturing%20Ready-brightgreen?style=for-the-badge)

### Professional EtherCAT Slave Evaluation Board Design

Industrial-grade multi-layer PCB evaluation board based on the Microchip LAN9252 EtherCAT controller with SPI interface support.

</div>

---

# 📌 Overview

This repository contains complete hardware design resources for a professional EtherCAT Slave Evaluation Board built around the **Microchip LAN9252 EtherCAT Controller**.

The project is designed for:

- Industrial Automation Systems
- Real-Time Embedded Applications
- EtherCAT Network Development
- Industrial IoT Platforms
- Embedded Hardware Prototyping
- Educational & Research Purposes

This repository includes manufacturing-ready PCB design files, schematics, bill of materials, PCB visualizations, and hardware documentation.

---

# ✨ Key Features

- EtherCAT Slave Communication Support
- LAN9252 EtherCAT Controller
- SPI Host Interface
- Multi-Layer PCB Design
- Industrial Hardware Architecture
- Optimized Signal Routing
- Manufacturing-Ready Gerber Files
- Complete Bill of Materials (BOM)
- PCB 3D Models & Renderings
- Professional Documentation

---

# ⚙️ Hardware Specifications

| Parameter | Specification |
|---|---|
| Main Controller | Microchip LAN9252 |
| Communication Protocol | EtherCAT |
| Host Interface | SPI |
| PCB Type | Multi-Layer PCB |
| PCB Thickness | 1.6mm |
| Operating Temperature | -40°C to +85°C |
| Input Voltage | 5V / 12V |
| Regulated Voltage | 3.3V |
| Ethernet Interface | RJ45 |
| Design Status | Manufacturing Ready |
| License | MIT |

---

# 📂 Repository Structure

```text
LAN9252-EtherCAT-SPI-EVB/
│
├── README.md
├── LICENSE
│
├── gerber/
│   └── LAN9252_EtherCAT_Gerber_v1.0.zip
│
├── schematic/
│   └── LAN9252_Schematic.pdf
│
├── pcb_layout/
│   └── LAN9252_PCB_Layout.pdf
│
├── bom/
│   └── BOM_LAN9252.csv
│
├── images/
│   ├── pcb_top.png
│   ├── pcb_bottom.png
│   ├── pcb_3d.png
│   └── schematic_preview.png
│
├── 3d_models/
│   └── pcb_model.obj
│
└── docs/
    ├── DESIGN_GUIDE.md
    └── CHANGELOG.md
```

---

# 📸 PCB Preview

## Top Layer PCB

<p align="center">
  <img src="images/pcb_top.png" width="900"/>
</p>

---

## Bottom Layer PCB

<p align="center">
  <img src="images/pcb_bottom.png" width="900"/>
</p>

---

## 3D PCB Render

<p align="center">
  <img src="images/pcb_3d.png" width="900"/>
</p>

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

# 📦 Included Design Files

## PCB Manufacturing Files
- Gerber Files
- Drill Files
- PCB Production Files

## Documentation
- Schematic PDF
- PCB Layout PDF
- Bill of Materials (CSV)
- Design Documentation

## Visualization
- PCB 3D Renderings
- Mechanical Models

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/AxayRam/LAN9252-EtherCAT-SPI-EVB.git
```

---

# 🏭 PCB Manufacturing

This design is prepared for professional PCB fabrication and assembly.

## Recommended PCB Parameters

| Parameter | Recommendation |
|---|---|
| PCB Material | FR4 |
| Layer Count | 4-Layer |
| Thickness | 1.6mm |
| Surface Finish | ENIG |
| Copper Weight | 1oz |
| Solder Mask | Green / Black |

---

# 🔌 Hardware Integration

- Connect the SPI interface to an external MCU
- Connect Ethernet through RJ45 connector
- Apply appropriate regulated power supply
- Verify SPI communication parameters
- Configure EtherCAT firmware stack

---

# 🌐 EtherCAT Technology

EtherCAT (Ethernet for Control Automation Technology) is a high-performance industrial Ethernet protocol designed for deterministic real-time communication.

## Advantages

- Ultra-Low Latency
- Deterministic Communication
- High-Speed Ethernet Performance
- Industrial Reliability
- Real-Time Data Exchange

---

# 🛠️ Design Highlights

## Signal Integrity
- Controlled impedance routing
- Optimized differential pair routing
- Reduced EMI/RFI interference

## Power Design
- Stable 3.3V regulation
- Decoupling capacitor network
- Industrial-grade filtering

## PCB Engineering
- Multi-layer stack-up
- Ground plane optimization
- Thermal-aware component placement

---

# 📋 Main Components

- LAN9252 EtherCAT Controller
- RJ45 Ethernet Connector
- SPI Interface Header
- Crystal Oscillator
- Power Regulation Circuit
- Passive Components
- Protection Circuits

---

# 📖 Documentation

| File | Description |
|---|---|
| README.md | Project Overview |
| DESIGN_GUIDE.md | Hardware Design Documentation |
| CHANGELOG.md | Version History |
| LICENSE | MIT License |

---

# 📜 License

This project is released under the MIT License.

You are free to:
- Use commercially
- Modify the design
- Distribute the files
- Use privately

Please include the original license and copyright notice.

---

# 🤝 Contributing

Contributions and improvements are welcome.

You can contribute by:
- Reporting issues
- Improving documentation
- Suggesting hardware optimizations
- Sharing integration examples

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
- Contribute improvements

---

# 📅 Version Information

| Item | Value |
|---|---|
| Version | v1.0 |
| Release Type | Initial Manufacturing Release |
| Status | Manufacturing Ready |
| Last Updated | April 2026 |

---

<div align="center">

### Industrial Embedded Hardware Design Project

Professional EtherCAT Slave Evaluation Board using Microchip LAN9252

</div>
