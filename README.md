# MCU Datalogger — KiCad PCB Project

An MCU-based datalogger board designed in KiCad 9, featuring a real-time clock (DS1337S) and onboard memory, built around an ATmega328P-AU.

## Branches

This repository uses branches to track different hardware revisions of the same design:

| Branch    | Description                                  |
|-----------|-----------------------------------------------|
| `main`    | Primary development branch                    |
| `2layer`  | 2-layer PCB variant                            |
| `4layer`  | 4-layer PCB variant (dedicated ground/power planes) |

Each branch contains its own schematic and PCB layout for that board revision. Gerbers for each variant are generated and stored per-branch.

## Features

- ATmega328P-AU microcontroller
- DS1337S real-time clock
- GPIO and serial header breakouts
- Designed and routed in KiCad 9.0

## Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/mhmdhamad/MCU-Datalogger-PCB-KiCad-.git
   ```
2. Check out the branch for the board revision you want:
   ```
   git checkout 2layer
   ```
3. Open `MCU Datalogger.kicad_pro` in KiCad 9.0 or later.

## License

This project is licensed under the [CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S)](LICENSE). You are free to use, study, modify, and manufacture this design, provided that any distributed modifications are released under the same license.

## Author

Mohammad — MSc Electronics Engineering, Lebanese International University
