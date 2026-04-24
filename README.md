# LAN9252 EtherCAT SPI Evaluation Board (EVB)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Hardware: PCB Design](https://img.shields.io/badge/Hardware-PCB%20Design-blue)](#)
[![EtherCAT Ready](https://img.shields.io/badge/EtherCAT-Ready-green)](#)

## Overview

The **LAN9252 EtherCAT SPI Evaluation Board** is a professional-grade PCB design for prototyping and developing EtherCAT slave devices using the Microchip LAN9252 EtherCAT processor with SPI interface. This board provides a complete hardware reference implementation suitable for industrial automation, robotics, and IoT applications.

### Key Features

- **EtherCAT Controller**: LAN9252 processor for real-time Ethernet communication
- **SPI Interface**: Serial Peripheral Interface for microcontroller integration
- **Industrial Grade**: Designed for manufacturing-ready deployment
- **Complete Documentation**: Gerber files, BOM, and design artifacts included
- **Optimized Layout**: Professionally routed PCB with impedance control considerations
- **Manufacturing Ready**: All necessary files for PCB fabrication

## Project Structure

```
LAN9252-EtherCAT-SPI-EVB/
├── README.md                                          # Project documentation
├── BOM_EVB_LAN9252_SPI_2026-04-24.csv                # Bill of Materials
├── Gerber_EVB_LAN9252_SPI_PCB_EVB_LAN9252_SPI_2026-04-24/  # PCB Gerber files
│   ├── Gerber_TopLayer.GTL                           # Top copper layer
│   ├── Gerber_BottomLayer.GBL                        # Bottom copper layer
│   ├── Gerber_TopSilkscreenLayer.GTO                 # Top component labels
│   ├── Gerber_BottomSilkscreenLayer.GBO              # Bottom labels
│   ├── Gerber_TopSolderMaskLayer.GTS                 # Top solder mask
│   ├── Gerber_BottomSolderMaskLayer.GBS              # Bottom solder mask
│   ├── Gerber_TopPasteMaskLayer.GTP                  # Top paste stencil
│   ├── Gerber_BottomPasteMaskLayer.GBP               # Bottom paste stencil
│   ├── Gerber_BoardOutlineLayer.GKO                  # Board edge cut
│   ├── Gerber_DocumentLayer.GDL                      # Documentation layer
│   ├── Drill_PTH_Through.DRL                         # Plated holes
│   ├── Drill_NPTH_Through.DRL                        # Non-plated holes
│   ├── Drill_PTH_Through_Via.DRL                     # Via holes
│   └── How-to-order-PCB.txt                          # PCB ordering guide
└── OBJ_PCB_EVB_LAN9252_SPI_2026-04-24/              # 3D Model files
    └── OBJ_PCB_EVB_LAN9252_SPI.mtl                   # Material definition
```

## Specifications

| Parameter | Value |
|-----------|-------|
| **Main Processor** | Microchip LAN9252 |
| **Communication Protocol** | EtherCAT (IEEE 802.3) over SPI |
| **Interface** | SPI (Serial Peripheral Interface) |
| **Date** | April 24, 2026 |
| **Status** | Manufacturing Ready |

## Bill of Materials (BOM)

The complete Bill of Materials is available in `BOM_EVB_LAN9252_SPI_2026-04-24.csv`. This file contains:
- Component designators
- Part names and values
- Footprints
- Reference quantities for assembly

### Key Components
- **LAN9252**: EtherCAT SPI Controller
- **RJ45 Connector**: Ethernet interface
- **Crystal Oscillator**: Clock reference for timing
- **Passive Components**: Resistors, capacitors for signal integrity
- **Decoupling**: Power supply filtering and protection

## PCB Files (Gerber Format)

All manufacturing files are included in standard Gerber format (.GER) and industry-standard drill format (.DRL):

### Signal Layers
- **Top Layer (GTL)**: Primary routing and component placement
- **Bottom Layer (GBL)**: Secondary routing and ground plane

### Mask & Silkscreen
- **Solder Mask**: Protects copper traces during wave/reflow soldering
- **Silkscreen**: Component labels and reference designators
- **Paste Mask**: Stencil for solder paste application

### Drill Files
- **PTH (Plated Through Holes)**: Components and vias
- **NPTH (Non-Plated Through Holes)**: Mechanical mounting
- **Via Drill**: Interconnections between layers

## Getting Started

### 1. PCB Fabrication

To order your PCB:

1. **Prepare Files**
   - Use all Gerber files from `Gerber_EVB_LAN9252_SPI_PCB_EVB_LAN9252_SPI_2026-04-24/` folder
   - Include the drill files for through-holes

2. **Select PCB Manufacturer**
   - Recommended: JLCPCB, PCBWay, OSHPARK, or similar
   - Refer to `How-to-order-PCB.txt` for detailed ordering instructions

3. **Upload Files**
   - Most manufacturers accept zipped Gerber files
   - Specify production quantity and options

4. **Component Assembly**
   - Use the BOM (`BOM_EVB_LAN9252_SPI_2026-04-24.csv`) for procurement
   - Choose SMT assembly service or hand-assemble if small volume

### 2. Hardware Integration

- Connect SPI interface to your microcontroller (STM32, Arduino, etc.)
- Connect Ethernet cable to RJ45 connector
- Apply appropriate power supply (refer to LAN9252 datasheet)
- Pull-up/pull-down resistors should be verified per datasheet

### 3. Firmware Development

For software integration:
- Download the LAN9252 EtherCAT stack from Microchip
- Configure SPI communication parameters
- Implement EtherCAT slave state machine
- Test with EtherCAT master tools

## Technical Resources

- **[LAN9252 Datasheet](https://www.microchip.com/en-us/product/LAN9252)** - Official device specifications
- **[EtherCAT Specification](https://www.ethercat.org/)** - EtherCAT protocol reference
- **[PCB Ordering Guide](Gerber_EVB_LAN9252_SPI_PCB_EVB_LAN9252_SPI_2026-04-24/How-to-order-PCB.txt)** - Manufacturing instructions

## Design Considerations

### Electrical
- All power supply rails include decoupling capacitors
- SPI clock traces are routed for signal integrity
- Ground planes provide low impedance return paths
- Ethernet traces are length-matched and impedance controlled

### Mechanical
- Board dimensions optimized for standard enclosures
- Mounting holes positioned for flexible installation
- Component placement minimizes EMI emissions
- Thermal considerations for continuous operation

### Manufacturing
- All components are available in active parts databases
- Design follows standard PCB manufacturing guidelines
- DFM (Design for Manufacturability) review completed
- Suitable for automated SMT assembly lines

## Revision History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | 2026-04-24 | Initial release |

## Contributing

Contributions and improvements are welcome! Please feel free to:
- Report issues and bugs
- Suggest design improvements
- Provide updated firmware examples
- Share integration experiences

To contribute:
1. Fork the repository
2. Create a feature branch
3. Make your improvements
4. Submit a pull request

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### What this means:
- ✅ Free for commercial use
- ✅ Free for private use
- ✅ Free for modification
- ✅ Free for distribution
- ⚠️ Include license and copyright notice

## Disclaimer

This hardware design is provided as-is for educational and prototyping purposes. While designed to professional standards:
- Verify all electrical specifications against datasheets
- Conduct thorough testing before production deployment
- Follow all applicable safety regulations and standards
- The author assumes no liability for issues arising from use of this design

## Support & Contact

For questions, issues, or suggestions:
- Open an Issue on GitHub
- Check existing issues and discussions first
- Provide detailed description of your question

## Acknowledgments

- **Microchip Technology** - LAN9252 EtherCAT processor
- **EtherCAT Technology Group** - EtherCAT protocol specification
- PCB design tools: Industry-standard CAD software
- Manufacturing partners and feedback from the embedded systems community

---

**Version**: 1.0  
**Last Updated**: April 24, 2026  
**Status**: Manufacturing Ready ✓

## Quick Links

- 🌐 [EtherCAT Official Website](https://www.ethercat.org/)
- 📊 [LAN9252 Product Page](https://www.microchip.com/en-us/product/LAN9252)
- 📚 [EtherCAT Device Design Guide](https://www.ethercat.org/en/technology.html)
- 🔧 [Industrial Protocol Information](https://en.wikipedia.org/wiki/EtherCAT)
