# NRF24L01 Custom Board Design  

## Overview  
This project is a **learning project** focused on the design and implementation of a **custom PCB for the NRF24L01 transceiver module**. It demonstrates how to integrate the NRF24L01 with microcontrollers for wireless communication in embedded systems.  

The design includes **schematics**, **PCB layout**, and **manual calculations**, providing a hands-on guide for creating a functional custom board while understanding its design considerations.

---

## Features  
- **Module**: NRF24L01 transceiver for 2.4 GHz wireless communication.  
- **Operating Voltage**: 3.3V.  
- **Power Supply**: Includes onboard LDO for stable operation.  
- **Connectivity**: SPI interface for seamless integration with microcontrollers.  
- **Antenna Options**: PCB trace antenna or external SMA connector for extended range.  
- **Design Tool**: Created using **Altium Designer**.  
- **Application Areas**: IoT, remote control systems, wireless sensors, and more.

---

## Project Structure  
The project files are organized as follows:  
- `Schematic`: Contains the circuit diagram of the custom board.  
- `PCB_Layout`: Includes PCB design files, Gerbers, and assembly details.  
- `Simulation_Results`: Optional signal integrity and power analysis results.  
- `3D_Models`: 3D visualization of the designed board.  

---

## Design Overview  

### Schematic  
The schematic covers all connections required for the NRF24L01 module:  
1. **Power Supply**: A 3.3V LDO regulator ensures stable power for the module.  
2. **SPI Interface**: Connections for SCK, MOSI, MISO, and CSN to communicate with a microcontroller.  
3. **Interrupt Pin**: An IRQ pin is provided for event handling.  
4. **Antenna Connection**: Option for onboard PCB antenna or an external SMA connector.  

### PCB Layout  
The PCB layout is optimized for reliable wireless performance, taking care of the following:  
- **Ground Plane**: A solid ground plane reduces noise and improves stability.  
- **Trace Impedance Matching**: Ensures proper signal integrity for the SPI interface and RF signals.  
- **Compact Design**: Minimizes size while maintaining functionality.  

---

## PCB Layout Images  

<img "Images/Layout.jpg">
---

## Learning Outcomes  
This project serves as a great starting point for:  
- Understanding **RF design principles** such as impedance matching and antenna integration.  
- Learning the fundamentals of PCB design for wireless communication modules.  
- Gaining experience in creating compact, efficient hardware designs.

---
