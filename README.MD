##Note i dont want funding of 16$ as this includes a part of a different project

# RP2040 Breadboard-Friendly Devboard

A compact RP2040 devboard designed for rapid prototyping and breadboard use. This board allows testing GPIOs, sensors, and ideas without soldering every change.

## What is this?
This project is a small PCB with an RP2040 microcontroller, USB-C power input, and breadboard-compatible headers. It is designed to allow quick circuit testing, firmware development, and learning without requiring a polished final product.

## Why I made it
I wanted a board that could power over USB and plug directly into a breadboard for rapid experimentation. By designing this board, I learned how to plan pinout, power, and I/O for a microcontroller, while also learning schematic design and PCB layout in KiCad.

## How it works
Power enters via USB-C and goes through basic regulation and decoupling capacitors for stability. The RP2040 handles I/O and communicates with peripherals like an IMU (ICM-20602). LEDs indicate power, BootSel, and GPIO activity. Breadboard headers allow plugging in sensors or modules quickly, and proper routing ensures signal integrity and safe operation.

### Key features
- USB-C powered RP2040 board  
- Breadboard-compatible header layout  
- LEDs for power, BootSel, and GPIO  
- Integrated IMU (ICM-20602) with required decoupling caps  
- Crystal oscillator for accurate timing  
- Boot configuration with button and pull-ups  

## What I learned
- Schematic clean ≠ correct: always check net names and pin mapping  
- QSPI pins on RP2040 must go to dedicated flash pins for booting  
- Routing power and USB signals is tricky; differential pairs and trace lengths matter  
- Component placement affects ease of routing and board functionality  
- Breadboard compatibility must be considered from the start  

##Images of pcb, sch, cost, bom, etc

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/My_Dev_Board.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/My_Dev_Board1.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/My_Dev_Board3.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/My_Dev_Board4.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/My_Dev_board_sch.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/Screenshot 2025-12-31 221019.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/Screenshot 2026-01-01 100546.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/Screenshot 2026-01-01 094838.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/Screenshot 2026-01-01 112238.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/Screenshot 2026-01-01 112358.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/Screenshot 2026-01-01 112407.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/Screenshot 2026-01-01 112504.png" />

<img width="299" height="552" alt="Screenshot 2025-11-30 204253" src="img/Screenshot 2026-01-01 112511.png" />





