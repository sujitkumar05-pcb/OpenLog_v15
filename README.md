# OpenLog_v15

## 1. Project Overview
OpenLog_v15 is a compact data logging system designed to record serial data onto a microSD card in a simple and reliable manner. It is commonly used for debugging, sensor data logging, and embedded system development. The module interfaces easily with microcontrollers via UART and operates with minimal configuration, making it suitable for both prototyping and long-term data collection applications.

-----

## 2. Key Learning Objectives

Understand serial (UART) communication and data logging concepts.

Learn how to interface a microSD card with embedded systems.

Gain experience in reliable data storage for debugging and monitoring.

Understand low-power, standalone logging module design.

Develop skills for integrating logging modules with microcontrollers.
-----

## 3. Tools & Software Used
- **KiCad EDA**
  - Schematic Editor  
  - PCB Layout Editor  
  - 3D Viewer
 
 ---

## 4. Project Files
- Schematic design files (`.kicad_sch`)  
- PCB layout files (`.kicad_pcb`)  
- 3D render images  
- Manufacturing-ready Gerber files  

---

## 5. Block-Level Working Explanation

Microcontroller (UART TX): Sends serial data to the OpenLog module.

UART Interface: Receives and transfers data reliably to the logger.

OpenLog Controller: Processes incoming data and manages file operations.

microSD Card: Stores the received data as sequential log files.

Power Supply Block: Provides regulated voltage for stable operation.

## 6. Bill of Materials (BOM)
|Sno.| Reference      | Qty | Value / Part            | Footprint                                                  |
| -- | -------------- | --- | ----------------------- | ---------------------------------------------------------- |
| 1  | C1             | 1   | 10 µF                   | Capacitor_SMD:C_1206_3216Metric                            |
| 2  | C2, C3         | 2   | 0.1 µF                  | Capacitor_SMD:C_1206_3216Metric                            |
| 3  | C4             | 1   | 0.1 µF                  | Capacitor_SMD:C_1210_3225Metric                            |
| 4  | D1             | 1   | Green LED               | LED_SMD:LED_0805_2012Metric                                |
| 5  | D2             | 1   | Blue LED                | LED_SMD:LED_0805_2012Metric                                |
| 6  | H1, H2, H3, H4 | 4   | Mounting Hole           | MountingHole:MountingHole_2.1mm                            |
| 7  | J1             | 1   | Pin Header 1×4          | Connector_PinHeader_2.54mm:PinHeader_1x04_P2.54mm_Vertical |
| 8  | J2             | 1   | Pin Header 1×6          | Connector_PinHeader_2.54mm:PinHeader_1x06_P2.54mm_Vertical |
| 9  | J3             | 1   | Micro SD Card Connector | Connector_Card:microSD_HC_Hirose_DM3AT-SF-PEJM5            |
| 10 | Q1             | 1   | 16 MHz Crystal          | Crystal:Crystal_SMD_MicroCrystal_MS1V-T1K                  |
| 11 | R1             | 1   | 330 Ω                   | Resistor_SMD:R_0805_2012Metric                             |
| 12 | R2, R3         | 2   | 1 kΩ                    | Resistor_SMD:R_0805_2012Metric                             |
| 13 | TP1            | 1   | Test Point              | Connector_PinHeader_1.27mm:PinHeader_1x01_P1.27mm_Vertical |
| 14 | U1             | 1   | MIC5205 (3.3 V LDO)     | Package_TO_SOT_SMD:SOT-23-5                                |
| 15 | U2             | 1   | ATmega328P-A            | Package_QFP:TQFP-32_7x7mm_P0.8mm                           |


## 7. Images & Renders

- **Schematic**
<img width="1175" height="829" alt="image" src="https://github.com/user-attachments/assets/51548d96-8109-4c72-9f08-3e4e0ad5a45e" />


- **PCB Layout**
 <img width="1316" height="856" alt="image" src="https://github.com/user-attachments/assets/2d9f11df-188c-42a4-971f-1e4831723043" />
 <img width="1237" height="852" alt="image" src="https://github.com/user-attachments/assets/5cd424a2-b8f3-47db-9056-47d5fc3d7cfa" />

- **3D View**
 <img width="1107" height="741" alt="image" src="https://github.com/user-attachments/assets/3989fd59-88da-4bd9-9c59-b8aba50b7770" />
 <img width="1047" height="823" alt="image" src="https://github.com/user-attachments/assets/b9838444-ab13-43a9-a3e4-fef075ffe60f" />

  
---

## 8. Disclaimer
This project is intended for educational and experimental purposes only. While the design follows standard engineering practices, it should be carefully reviewed and tested before use in real-world applications. The author is not responsible for any damage, data loss, or issues arising from improper use or modification of this design.
---

## 9. Author
- **Name:** SUJIT KUMAR
- **Toolchain:** KiCad EDA  



