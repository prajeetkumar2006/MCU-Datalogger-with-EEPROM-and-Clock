# MCU-Datalogger-with-EEPROM-and-Clock
A custom-designed ATmega328P-based data logger PCB featuring dual I²C EEPROMs and a DS1337 real-time clock for reliable time-stamped data storage.

This project is a microcontroller-based data logger designed using KiCad. It uses an ATmega328P as the main controller, a DS1337 real-time clock for accurate timekeeping, and dual 24LC1025 EEPROMs for non-volatile data storage. The system logs sensor or system data with date and time information and provides I²C, UART, and ICSP interfaces for communication, programming, and debugging.

# Features
- Microcontroller: ATmega328P-AU (16 MHz)
- Real-time clock: DS1337S with 32.768 kHz crystal
- Non-volatile memory: 2 × 24LC1025 EEPROM (I²C)
- Connectivity: I²C header, UART (RX/TX) header, GPIO header, 6-pin ICSP
- Indicators: 2 status LEDs
- Power: Coin-cell Battery (BT1) for RTC backup
- Board: 2-layer PCB; 87.63 mm × 39.116 mm; 4 mounting holes
- KiCad version: 9.0.0

## Hardware Components

### Integrated Circuits (ICs)
- ATmega328P – Main microcontroller
- DS1337 – Real-Time Clock (RTC)
- 24LC1025 – I2C EEPROM (x2)

### Resistors (R)
- R1 – 330 Ω
- R2, R3 – 4.7 kΩ
- R4 – 10 kΩ

### Capacitors (C)
- C1, C2 – 22 pF
- C3, C4 – 100 nF
- C5 – 10 µF

### Crystals (X)
- X1 – 16 MHz
- X2 – 32.768 kHz

### Connectors / Jumpers (J)
- ICSP header – MCU programming
- UART header – Serial communication
- I2C header – External peripherals
- Power header – VCC and GND
