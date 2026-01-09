# Relay_Module

This is the repo for a relay control module that im making, designed to work with an ESP32 microcontroller but will hopefully be compatible with others.

<img width="854" height="516" alt="image" src="https://github.com/user-attachments/assets/4fd68a51-6c1e-4699-924d-47b38c5f7015" />



## Features

- 5V Power Pin header
 
- 0V Ground Pin header

- 3 ressistors

- A capacitor

- HK4100F-5V Relay

- 3.3V ESP32 control pin header

## Images

Here are pictures of my pcb:

### Schematic
<img width="1292" height="589" alt="image" src="https://github.com/user-attachments/assets/22a9f894-8902-4849-b9e1-4f197aa39d8d" />

### PCB
<img width="771" height="382" alt="image" src="https://github.com/user-attachments/assets/85328ffa-471e-43ca-a6e7-e8d6236d5a34" />

## BOM
| Id | Reference        | Component                | Footprint                                        | Quantity | RS Stock No | Title                                            | Manufacturer Part No | Unit Price (£) |
| -- | ---------------- | ------------------------ | ------------------------------------------------ | -------- | ----------- | ------------------------------------------------ | -------------------- | -------------- |
| 1  | K1               | 5 V SPDT Relay           | Relay_SPDT_HK4100F                               | 1        | 7932170     | Hongfa SPDT PCB Relay, 5 V Coil, 10 A            | HK4100F-DC5V-SHG     | 1.45           |
| 2  | R3               | 10 kΩ Resistor           | R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | 1        | 7077749     | RS PRO 10 kΩ Carbon Film Resistor 0.25 W ±5%     | —                    | 0.14           |
| 3  | POWER1           | 2-pin Header             | PinHeader_1x02_P2.54mm_Horizontal                | 1        | 2518076     | RS PRO 2-Way Right-Angle PCB Pin Header, 2.54 mm | —                    | 0.36           |
| 4  | R1, R2           | 1 kΩ Resistor            | R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | 2        | 7077622     | RS PRO 1 kΩ Carbon Film Resistor 0.25 W ±5%      | —                    | 0.14           |
| 5  | Q1               | NPN Transistor           | TO-92_Inline                                     | 1        | 5441994     | ON Semiconductor BC547B NPN Transistor, 100 mA   | BC547B               | 0.18           |
| 6  | D2               | Red LED 5 mm             | LED_D5.0mm                                       | 1        | 2285972     | Kingbright Red LED 2 V 5 mm Through-Hole         | L-53ID               | 0.17           |
| 7  | D1               | Flyback Diode            | D_DO-15_P10.16mm_Horizontal                      | 1        | 8150070     | Vishay 1N4007 Rectifier Diode 1 A 1000 V         | 1N4007-E3/54         | 0.12           |
| 8  | C1               | 100 nF Ceramic Capacitor | C_Disc_D5.0mm_W2.5mm_P5.00mm                     | 1        | 8523262     | Kemet 100 nF Ceramic Disc Capacitor 50 V         | C322C104K5R5TA       | 0.16           |
| 9  | OUTPUT1          | 3-way Terminal Block     | TerminalBlock_Phoenix_MKDS-1,5-3-5.08            | 1        | 2204283     | Phoenix Contact 3-Way PCB Terminal Block 5.08 mm | MKDS 1,5/3-5.08      | 1.05           |
| 10 | ESP32_GPIO_CONN1 | 1-pin Header             | PinHeader_1x01_P2.54mm_Horizontal                | 1        | 2518072     | RS PRO 1-Way Right-Angle PCB Pin Header, 2.54 mm | —                    | 0.18           |
