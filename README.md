# IEEE LED Matrix Board

A KiCad hardware design for an LED matrix display board, built for IEEE. The board uses an Arduino Nano Every microcontroller and a MAX7219 LED driver to control multiple LED display modules.

## Circuit Overview

| Component | Description |
|-----------|-------------|
| Arduino Nano Every | Main microcontroller (ATmega4809) |
| MAX7219 | 8-digit serial LED display driver (Maxim Integrated) |
| TDCR1060M (x2) | Vishay LED display units |
| VS-1213-67-160GF (x3) | LED matrix display modules |

The design supports multiple voltage rails (1V, 3.3V, 5V) and uses passive components for current limiting and decoupling.

## Project Status

- [x] Schematic design
- [ ] PCB layout
- [ ] Firmware
- [ ] Fabrication

## Tools

- [KiCad 9.0](https://www.kicad.org/) — Schematic and PCB design

## Getting Started

1. Install [KiCad 9.0](https://www.kicad.org/download/) or later
2. Clone this repository
3. Open `LedMatrix.kicad_pro` in KiCad

## Objective

This board was developed as a intro to kicad/PCB workshop board.

## License

This project is developed by Luca Sburlino. Contact the maintainers for usage terms.
