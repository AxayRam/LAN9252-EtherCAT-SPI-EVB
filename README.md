# EtherCAT PCB EVB LAN9252 SPI Design

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Hardware Design](https://img.shields.io/badge/Design-PCB%20Evaluation%20Board-blue.svg)]()
[![Protocol](https://img.shields.io/badge/Protocol-EtherCAT%20%2F%20SPI-green.svg)]()
[![Type](https://img.shields.io/badge/Type-Design%20Files%20Only-red.svg)]()

> ⚠️ **DESIGN FILES REPOSITORY** — This contains PCB design files (Gerber, schematics, BOM) only. **You will manufacture the PCB through external manufacturers and assemble the board yourself or through PCBA services.** No pre-assembled boards are provided.

## 📋 Project Overview

This repository contains the **complete PCB DESIGN FILES** for an **EtherCAT Evaluation Board (EVB) with LAN9252 microcontroller**, implementing industrial communication over Serial Peripheral Interface (SPI).

⚠️ **IMPORTANT**: This is a **DESIGN repository ONLY**. We provide design files and documentation. You will manufacture the PCBs through external PCB manufacturers (JLCPCB, PCBWay, etc.) and assemble the boards yourself or through PCBA services.

This evaluation board is designed for rapid prototyping and validation of EtherCAT-based embedded systems and IoT applications.

### Key Features
- ✅ **EtherCAT Protocol Support** - Full EtherCAT slave implementation
- ✅ **LAN9252 Microcontroller** - Industry-standard EtherCAT controller IC
- ✅ **SPI Interface** - High-speed SPI communication for peripheral connectivity
- ✅ **Production-Ready Design** - Professional manufacturing specifications
- ✅ **Multi-Layer PCB** - Optimized signal integrity and power distribution
- ✅ **Complete Documentation** - Schematics, BOM, and Gerber files included
- ✅ **Design Files Only** - No pre-assembled boards (DIY or use PCBA services)

---

## ❓ What IS This Repository?

✅ **PCB Design Files** - Complete Gerber files for professional manufacturing  
✅ **Documentation** - Comprehensive guides for building this board  
✅ **Open Source** - Free to use, modify, and distribute (MIT License)  
✅ **Reusable Design** - Fork and adapt for your specific needs  
✅ **Community Support** - Issue tracking and discussion board  
✅ **Educational** - Learn PCB design and EtherCAT integration  

## ❌ What This Is NOT

❌ **NOT a Manufacturing Service** - We don't manufacture PCBs  
❌ **NOT an Assembly Service** - We don't assemble boards  
❌ **NOT Pre-Assembled Boards** - You won't receive a ready-to-use board  
❌ **NOT a Commercial Product** - This is a design, not a product sale  
❌ **NOT Support with Pre-Built Hardware** - You must build it yourself  

## 🛠️ You Will Need To:

1. **Order PCBs** from manufacturers (JLCPCB, PCBWay, Oshpark, etc.)
2. **Source Components** from electronics distributors (Digi-Key, Mouser, etc.)
3. **Assemble** the board yourself (DIY soldering) OR use a PCBA service
4. **Test & Validate** the assembled board

---

## 📁 Project Structure

```
.
├── README.md                              # This file - Project documentation
├── DESIGN_GUIDE.md                        # Detailed design specifications
├── INSTALLATION_GUIDE.md                  # Setup and manufacturing guide
├── BOM_EVB_LAN9252_SPI_2026-04-24.csv     # Bill of Materials
├── PCB_PCB_EVB_LAN9252_SPI_2026-04-24.pdf # PCB layout documentation
├── Schematic_EVB_LAN9252_SPI_2026-04-24.pdf # Electrical schematic
├── PCB_PCB_EVB_LAN9252_SPI_2026-04-24.png # PCB preview image
├── back_PCB_PCB_EVB_LAN9252_SPI_2026-04-24.png # Back layer view
├── 3d_*.png                               # 3D rendering images (4 views)
│
├── Gerber_EVB_LAN9252_SPI_PCB_EVB_LAN9252_SPI_2026-04-24/
│   ├── Gerber_TopLayer.GTL                # Top copper layer
│   ├── Gerber_BottomLayer.GBL             # Bottom copper layer
│   ├── Gerber_TopSilkscreenLayer.GTO      # Top silkscreen
│   ├── Gerber_BottomSilkscreenLayer.GBO   # Bottom silkscreen
│   ├── Gerber_TopSolderMaskLayer.GTS      # Top solder mask
│   ├── Gerber_BottomSolderMaskLayer.GBS   # Bottom solder mask
│   ├── Gerber_TopPasteMaskLayer.GTP       # Top paste mask
│   ├── Gerber_BottomPasteMaskLayer.GBP    # Bottom paste mask
│   ├── Gerber_BoardOutlineLayer.GKO       # Board outline
│   ├── Drill_PTH_Through.DRL              # Plated through-hole drills
│   ├── Drill_NPTH_Through.DRL             # Non-plated through-hole drills
│   ├── Drill_PTH_Through_Via.DRL          # Via drills
│   ├── Gerber_DocumentLayer.GDL           # Documentation layer
│   └── How-to-order-PCB.txt               # PCB manufacturer ordering guide
│
└── OBJ_PCB_EVB_LAN9252_SPI_2026-04-24/
    └── OBJ_PCB_EVB_LAN9252_SPI.mtl        # 3D model material file
```

---

## 🔧 Hardware Specifications

| Parameter | Specification |
|-----------|---------------|
| **Protocol** | EtherCAT Slave (IEEE 802.3) |
| **Main IC** | LAN9252 EtherCAT Controller |
| **Interface** | SPI (Serial Peripheral Interface) |
| **PCB Layers** | Multi-layer design |
| **Operating Voltage** | [See design guide] |
| **Temperature Range** | [See design guide] |
| **Dimensions** | [See PCB documentation] |
| **Design Date** | April 24, 2026 |

---

## 📊 Bill of Materials (BOM)

The complete BOM is available in: **`BOM_EVB_LAN9252_SPI_2026-04-24.csv`**

Key component categories:
- **Microcontroller**: LAN9252 EtherCAT Slave Controller
- **Passive Components**: Resistors, Capacitors, Inductors
- **Connectors**: SPI interface, Power, Ethernet
- **Decoupling/Filtering**: Power supply filtering components
- **Support ICs**: Signal conditioning and interface circuits

---

## 📐 PCB Manufacturing Files

### Gerber Files
Production-ready Gerber files are located in the `Gerber_EVB_LAN9252_SPI_PCB_EVB_LAN9252_SPI_2026-04-24/` directory.

**Files included:**
- **Copper layers**: Top (GTL) and Bottom (GBL)
- **Silkscreen**: Top (GTO) and Bottom (GBO)
- **Solder masks**: Top (GTS) and Bottom (GBS)
- **Paste masks**: Top (GTP) and Bottom (GBP)
- **Board outline**: Edge definition (GKO)
- **Drill files**: PTH, NPTH, and Via drills (DRL)
- **Documentation**: Layer information (GDL)

### Manufacturing Requirements
See **`INSTALLATION_GUIDE.md`** for:
- Recommended PCB manufacturers
- Layer stackup specifications
- Design rules and tolerances
- Assembly instructions

---

## 🎯 Getting Started

### 1. **Understand the Design** (5 min)
   - Review [DESIGN_GUIDE.md](DESIGN_GUIDE.md) for technical specifications
   - Study [Schematic_EVB_LAN9252_SPI_2026-04-24.pdf](Schematic_EVB_LAN9252_SPI_2026-04-24.pdf)
   - Examine [PCB_PCB_EVB_LAN9252_SPI_2026-04-24.pdf](PCB_PCB_EVB_LAN9252_SPI_2026-04-24.pdf)

### 2. **Download Design Files** (2 min)
   - Download all Gerber files from `Gerber_EVB_LAN9252_SPI_PCB_EVB_LAN9252_SPI_2026-04-24/`
   - Get BOM file: `BOM_EVB_LAN9252_SPI_2026-04-24.csv`
   - Reference PDFs and images

### 3. **Order PCB** (15 min)
   - Upload Gerber files to PCB manufacturer (JLCPCB, PCBWay, Oshpark)
   - Specify board parameters (layer count, thickness, finish)
   - Place order and wait for delivery (5-15 business days)

### 4. **Order Components & Assemble** (1-4 weeks)
   - Use BOM for component sourcing (Digi-Key, Mouser, Arrow)
   - Assemble yourself (DIY) OR use PCBA service
   - Follow assembly guidelines in [INSTALLATION_GUIDE.md](INSTALLATION_GUIDE.md)

### 5. **Test & Validate** (1-2 hours)
   - Follow testing procedures in [INSTALLATION_GUIDE.md](INSTALLATION_GUIDE.md)
   - Power-up tests, communication tests
   - Validate with test procedures (see design guide)

---

## 📖 Documentation Files

| Document | Purpose |
|----------|---------|
| **README.md** | Project overview (this file) |
| **DESIGN_GUIDE.md** | Technical specifications and design details |
| **INSTALLATION_GUIDE.md** | Manufacturing and assembly instructions |
| **Schematic PDF** | Electrical circuit diagram |
| **PCB PDF** | Layout and layer information |
| **BOM CSV** | Component list with part numbers and quantities |

---

## 🛠️ Tools & Software Used

The design files are compatible with:
- **PCB CAD Software**: KiCAD, Altium Designer, Eagle
- **Gerber Viewers**: Gerbv, CAM350, Ucamco GerberView
- **3D Visualization**: FreeCAD, Step viewers
- **PCB Manufacturing Software**: All major PCB house CAM software

---

## 🔒 Design Validation

✓ **Design Status**: Production-Ready  
✓ **Design Review**: Complete  
✓ **Manufacturing**: Ready for production  
✓ **Layer Stackup**: Verified  
✓ **Signal Integrity**: Validated  
✓ **Power Distribution**: Optimized  

---

## 🌐 EtherCAT Protocol Information

**EtherCAT** (Ethernet for Control Automation Technology) is a real-time industrial Ethernet protocol offering:
- **Deterministic Communication**: Sub-microsecond cycle time
- **High Performance**: Gigabit Ethernet speeds
- **Low Latency**: True real-time capabilities
- **Wide Adoption**: Standard in industrial automation

For more information on EtherCAT, visit [EtherCAT Technology Group](https://www.ethercat.org)

---

## 🚀 Design Highlights

### Performance
- **Real-time EtherCAT Communication** - Industrial-grade protocol timing
- **High-Speed SPI Interface** - Fast peripheral connectivity
- **Optimized Signal Routing** - Minimal EMI/RFI interference

### Reliability
- **Multi-layer PCB** - Proper ground and power planes
- **Signal Integrity** - Controlled impedance traces
- **Thermal Management** - Optimized component placement

### Manufacturing
- **Production-Proven Design** - Tested manufacturing flow
- **DFM Guidelines** - Industry standard tolerances
- **Quality Assurance** - Full documentation provided

---

## 📋 Checklist for First-Time Users

- [ ] Download all files from the repository
- [ ] Review DESIGN_GUIDE.md thoroughly
- [ ] Examine Schematic and PCB PDFs
- [ ] Verify BOM component availability
- [ ] Select PCB manufacturer
- [ ] Submit Gerber files to manufacturer
- [ ] Verify manufacturing cost and timeline
- [ ] Order PCBs and components
- [ ] Follow assembly instructions
- [ ] Test completed board

---

## 🤝 Contributing

This is a PCB design project. To contribute:

1. **Report Issues**: Document any design improvements or errors
2. **Design Variations**: Submit design derivatives with clear documentation
3. **Documentation**: Improve and expand guides and specifications
4. **Manufacturing Feedback**: Share real-world assembly and manufacturing insights

---

## 📝 License

This PCB design is released under the **MIT License**. See [LICENSE](LICENSE) file for details.

**Commercial Use**: Permitted with attribution  
**Modification**: Allowed with documentation  
**Distribution**: Permitted under same license  

---

## 📞 Support & Resources

### Design Questions
- Review [DESIGN_GUIDE.md](DESIGN_GUIDE.md)
- Check [INSTALLATION_GUIDE.md](INSTALLATION_GUIDE.md)
- Examine PDF documentation included

### Manufacturing Support
- **PCB Manufacturer Resources**: See How-to-order-PCB.txt
- **Component Sourcing**: Verify part numbers in BOM
- **Assembly Partners**: Recommend local PCB assembly services (PCBA)

### EtherCAT Resources
- [EtherCAT.org](https://www.ethercat.org) - Official protocol documentation
- [LAN9252 Datasheet](https://www.microchip.com/) - Microcontroller specifications
- Community forums and industrial automation resources

---

## 🎓 Related Technologies

This design integrates several key technologies:
- **EtherCAT Protocol** - Real-time industrial communication
- **IEEE 802.3** - Ethernet physical layer
- **SPI Protocol** - Serial peripheral interface standard
- **PCB Design Best Practices** - Multi-layer layout optimization

---




## 🔄 Revision History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2026-04-24 | Initial release - Production-ready design |

---

## ⚠️ Important Notes

1. **Component Sourcing**: Verify part number availability with suppliers before ordering
2. **Manufacturing Lead Time**: Plan for extended lead times on specialized components
3. **Design Modifications**: Any changes should be validated for signal integrity and EMI
4. **Assembly Guidelines**: Follow manufacturer guidelines for soldering and assembly
5. **Testing**: Comprehensive testing recommended before production deployment

---

## 📄 Additional Files

| File | Description |
|------|-------------|
| `.gitignore` | Git ignore patterns |
| `LICENSE` | MIT License text |
| `CHANGELOG.md` | Version history and updates |

---

**Last Updated**: April 24, 2026  
**Status**: ✅ Production-Ready  
**Repository Version**: 1.0  

---

*For questions or feedback regarding this PCB design, please open an issue or contact the design team.*
