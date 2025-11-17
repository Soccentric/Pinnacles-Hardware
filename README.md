# Pinnacles-Hardware

## 🌟 Welcome to Pinnacles-Hardware - Open Source Edge Computing Platform

**Power-Efficient Innovation for the IoT Era**

This repository contains the complete design schematics, Bill of Materials (BOM), and technical documentation for our Pinnacles-Hardware platform - an NXP i.MX 93/95 based solution engineered for power-constrained edge applications. We're excited to open-source these designs to empower developers worldwide to create energy-efficient, intelligent IoT devices that push the boundaries of what's possible at the edge.

![Pinnacles-Hardware Platform](Pinnacles-Hardware.jpg)

### 🎯 Our Mission
Soccentric is committed to advancing edge computing through open collaboration. By sharing our Pinnacles platform, we strive to:
- **Enable Sustainable Computing**: Provide power-efficient hardware templates for eco-friendly devices
- **Accelerate IoT Development**: Offer proven designs that reduce time-to-market
- **Foster Audio Innovation**: Support the creation of next-generation audio and multimedia devices
- **Build Inclusive Technology**: Make advanced computing accessible to all developers

### 📋 What's Included
- **Full Hardware Designs**: Complete schematics for i.MX 93/95 based platforms
- **Comprehensive BOM**: Detailed component specifications with power optimization notes
- **Audio-Focused Interfaces**: Specialized audio and multimedia connectivity designs
- **Power Management Schematics**: Advanced power delivery and battery management circuits
- **Thermal Design**: Heat dissipation solutions for compact form factors
- **EMI/EMC Considerations**: Design guidelines for electromagnetic compatibility

**Author:** Sandesh Ghimire  
**©** Sandesh@soccentric.com

## Overview
NXP i.MX 93/95 SOM based hardware platform optimized for power-efficient edge computing with integrated AI acceleration. These System-on-Modules combine high-performance processing with rich multimedia capabilities, ideal for industrial IoT, automotive, and consumer applications requiring low power consumption.

## Key Specifications
- **Processor**: 1-2x Arm Cortex-A55 @ up to 1.7GHz + Arm Cortex-M33 @ 250MHz
- **AI Acceleration**: Arm Ethos-U65 microNPU for efficient ML inference
- **Memory**: Up to 3.7GT/s LPDDR4/LPDDR4X with inline ECC
- **Storage**: 3x SD 3.0/SDIO3.0/eMMC5.1, Octal SPI NOR/NAND
- **Security**: EdgeLock secure enclave with hardware-based security
- **Operating Temperature**: -40°C to +125°C for harsh environments

## Interfaces and Connectivity
All platforms have:
1. **Camera Interface**: 1x 2-lane MIPI-CSI (1080p60) + 8-bit parallel YUV/RGB
2. **Display Interface**: 1x MIPI-DSI (1080p60, 4-lane), 1x LVDS (720p60, 4-lane), 24-bit parallel RGB
3. **USB**: 2x USB 2.0 Type C with PHY
4. **UART**: 8x UART interfaces
5. **I2C**: 8x I2C interfaces
6. **SPI**: 8x SPI interfaces
7. **Ethernet**: 2x Gigabit Ethernet with AVB and IEEE 1588 TSN support
8. **CAN FD**: 2x CAN FD interfaces
9. **I3C**: 2x I3C interfaces for advanced sensor connectivity
10. **ADC**: 1x 4-channel 12-bit ADC
11. **FlexIO**: 2x 32-pin FlexIO interfaces (camera, bus, or serial I/O)
12. **Audio**: 7x I2S TDM (32-bit @ 768KHz), 8-channel PDM microphone input, SPDIF Tx/Rx, MQS output

## Capabilities
- **AI/ML Processing**: Efficient neural network inference with Ethos-U65 NPU
- **Audio Processing**: Advanced audio capture and processing with multiple codecs
- **Video Processing**: Hardware-accelerated video encoding/decoding
- **Real-time Control**: Dual-core Cortex-M33 for deterministic real-time tasks
- **Industrial Communication**: TSN-enabled Ethernet for Industry 4.0 applications
- **Sensor Fusion**: Rich sensor interfaces for IoT and automation
- **Low Power Operation**: Optimized for battery-powered and energy-constrained devices
- **Secure Computing**: Hardware security features for trusted execution

## Software Ecosystem
- **Linux OS**: Full Linux support with Yocto Project
- **FreeRTOS**: Real-time operating system for Cortex-M33
- **eIQ Toolkit**: AI development environment for edge ML applications
- **MCUXpresso SDK**: Comprehensive development tools and middleware

## Supported Operating Systems
- Linux (Yocto-based)
- FreeRTOS
- Green Hills INTEGRITY
- QNX
- VxWorks

## Applications
- Industrial automation and control systems
- Smart home and building automation
- Audio/video receivers and soundbars
- Automotive infotainment and cluster displays
- Medical devices and patient monitoring
- IoT gateways and edge nodes
- Wearable devices and hearables
- Public address and audio distribution systems

## Additional Features
- **Power Management**: Advanced power domains for optimal energy efficiency
- **Hardware Compositor**: Real-time graphics composition and blending
- **EdgeLock Security**: Comprehensive security framework with secure boot
- **Functional Safety**: Support for safety-critical applications
- **Extended Temperature**: Operation in extreme environmental conditions
- **Rich Ecosystem**: Extensive partner network and development resources

## 🚀 Getting Started

### Prerequisites
- NXP i.MX 93/95 System-on-Module
- PCB assembly equipment
- Audio testing tools (for audio-focused designs)
- MCUXpresso SDK

### Quick Start
1. **Review Schematics**: Examine the main board design in `schematics/`
2. **BOM Verification**: Check component power ratings in `bom/`
3. **PCB Fabrication**: Use manufacturing files in `pcb/`
4. **Power Testing**: Validate power delivery circuits first
5. **Audio Calibration**: Test audio interfaces with provided scripts

### Development Environment
- **MCUXpresso IDE**: NXP's integrated development environment
- **Yocto Project**: For custom Linux distributions
- **eIQ Toolkit**: AI development for edge applications
- **FreeRTOS**: Real-time operating system support

## 🤝 Contributing

Help us build the future of power-efficient computing!

### Ways to Contribute
- **Power Optimization**: Share power consumption improvements
- **Audio Enhancements**: Contribute audio processing improvements
- **Safety Features**: Add functional safety enhancements
- **Documentation**: Expand guides for different use cases
- **Testing**: Provide test results and validation data

### Development Workflow
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/power-optimization`)
3. Implement and test your changes
4. Document power/thermal impacts
5. Submit a Pull Request with detailed testing results

### Guidelines
- Include power consumption measurements
- Test thermal performance thoroughly
- Validate EMI/EMC compliance
- Follow NXP's i.MX design guidelines

## 📄 License

CERN Open Hardware Licence Version 2 - Permissive. Full license text in [LICENSE](LICENSE).

This permissive license allows commercial use and derivative works with attribution requirements.

## 📞 Support & Community

- **Issues**: [GitHub Issues](https://github.com/soccentric/Pinnacles-Hardware/issues)
- **Discussions**: [GitHub Discussions](https://github.com/soccentric/Pinnacles-Hardware/discussions)
- **NXP Community**: Connect with i.MX developers worldwide
- **Email**: hardware@soccentric.com for partnerships

## 🙏 Acknowledgments

- NXP Semiconductors for the i.MX platform
- Our community of power-efficient computing advocates
- The open hardware movement enabling global collaboration

---

**Efficient by Design, Powerful by Nature - Soccentric**