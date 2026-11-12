# IRONMAN SHIELD
### Custom Arduino Uno R3 Shield
A custom shield has been designed for Arduino Uno R3.
The shield includes several practical hardware features including temperature
sensing, servo interface, MOSFET interface, indication LEDS and power choice options.

## Demo Video

▶️ [lapse link](https://youtu.be/8z416_anAGs)

## lapse link

▶️ [lapse link](https://lapse.hackclub.com/timelapse/m8AzgBOMNNnI)

## Project
### 3D PCB Representation
![IRONMAN SHIELD 3D PCB](image/3d.png)
### PCB Layout
![IRONMAN SHIELD PCB](image/pcb.png)
### Circuit Schematic
![IRONMAN SHIELD Schematic](image/schematic.png)

## Repository Structure

| Folder/File | Description |
|---|---|
| PCB file/ | EasyEDA PCB project source |
| Gerber file/ | PCB manufacturing files |
| SCHEMATIC FILE/ | Circuit schematic |
| OBJ file/ | 3D PCB model |
| BILL OF MATRIAL/ | Bill of Materials |
| image/ | Project images |
| README.md | Project documentation |

## PCB Design Files
The editable PCB design file is stored in:

`PCB file/Arduino-shield.json`
The Gerber files are provided for PCB fabrication.
The schematic and 3D model files are also included in this repository.

## Bill of Materials (BOM)

The following table contains the components used in the project.

| Component | Designator | Quantity | Unit Price (USD) |
|---|---|---:|---:|
| 100nF | C1,C2,C4,C5,C6 | 5 | $0.016 |
| 100uF | C3 | 1 | $0.571 |
| S1A-13-F | D1 | 1 | $0.075 |
| 220S-1*2P | J5 | 1 | $0.112 |
| 22032031 | J6,J7 | 2 | $0.157 |
| 68000-103HLF | J8 | 1 | $0.283 |
| 22272021 | J9 | 1 | $0.148 |
| FC-2012HRK-620D | LED1 | 1 | $0.014 |
| IRF540NLPBF | Q1 | 1 | $4.965 |
| 10kΩ | R1,R2,R3,R7 | 4 | $0.003 |
| 560Ω | R4,R5 | 2 | $0.003 |
| 0Ω | R6 | 1 | $0.005 |
| TMP75AIDR | U1 | 1 | $0.297 |
| LEDGREEN0805 | U2 | 1 | TBD |
| 22032081 | J1,J3 | 2 | $1.237 |
| 22032061 | J2 | 1 | $0.495 |
| 22032101 | J4 | 1 | $1.661 |

**component Subtotal: $11.512 USD**

Note: U2 component price is not available.
The subtotal excludes PCB fabrication, PCBA assembly,
shipping and taxes.

## PCB Fabrication Cost

Manufacturer: JLCPCB

PCB fabrication quotation: Pending.
Final cost will depend on board specifications
and order quantity.

## PCBA Assembly Cost

Assembly Manufacturer: JLCPCB

PCBA assembly quotation: Pending.

The final assembly cost will be updated
after receiving the official quotation.
## How build physically

### 1. Download the Project

You can download the repository as a ZIP file.

### 2. Load the Design

To open the design:
open easyeda on any browser [EasyEDA](https://easyeda.com/)
Open and upload the schematic and PCB files.

### 3. Manufacture PCB

To make your PCB:

Upload the Gerber Files to a PCB Manufacturer

Place your order.

### 4. Assemble & Test

Once you receive your PCB:
Solder the components onto the board using the schematic & BOM.
Test the Servo & MOSFET interfaces with appropriate external hardware.


## Project Status

Current Deliverables: Schematic, PCB, 3D Model, BOM & Gerber Files.
only virtule project not physical

Designed By: dipender

Project Name: IRONMAN SHIELD

Design Date: 29th October 2026
