# RF to USB Dongle – STM32L432 + nRF24L01

This project is a compact **RF-to-USB dongle** built using an **STM32L432KBU** microcontroller and an **nRF24L01** 2.4 GHz transceiver module.  
The device receives RF data wirelessly and transmits it to a host computer over USB.

## 🔧 Features

- **MCU**: STM32L432KBU (ARM Cortex-M4, ultra-low power)
- **RF Module**: nRF24L01 (2.4 GHz transceiver)
- **USB Interface**: Native USB device for communication with PC or host
- **SPI Interface**: Used to communicate with the nRF24L01
- **Low Power Operation**: Suitable for battery-powered wireless systems
- **Compact Design**: USB dongle-style form factor

## 🎯 Applications

- Wireless data receiver (e.g., for sensors, remotes)
- USB dongle for custom RF communication protocols
- PC bridge for STM32-based RF networks
- Debugging/logging tool for embedded wireless systems

## 🧱 PCB Details

- 4-layer PCB
- **Micro-USB (Type B)** connector
- On-board 3.3V LDO regulator for nRF24L01 and STM32
- SMA antenna

## 🧱 PCB Stackup

This project uses a 4-layer PCB for better signal integrity and power distribution:

1. **Top Layer (Layer 1)** – Signal  
2. **Inner Layer 1 (Layer 2)** – Ground (GND)  
3. **Inner Layer 2 (Layer 3)** – 3.3V Power Plane  
4. **Bottom Layer (Layer 4)** – Signal
