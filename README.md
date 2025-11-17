# Pinnacles-Hardware

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