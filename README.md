# Circuit Design — ESP32 & IoT Lab Exercise

**Course:** Embedded Systems & IoT (Aug – Nov 2026)  
**Author:** Mawira Victor  
**Institution:** BCNS — Year 3, Semester 2

---

## Overview

This repository contains the deliverables for the **Lab Exercise: Schematics with ESP32**, covering:

- **Part A:** Analysis of series and parallel resistor circuits
- **Part B:** Schematic design of an ESP32 + DHT22 temperature and humidity sensor circuit

All schematics were designed using **EasyEDA** and exported as PDF documents.

---

## Repository Contents

| File | Description |
|------|-------------|
| `Part A.pdf` | Circuit calculations and analysis for Part A |
| `Lab Exersice using ESP32 schematic.docx` | ESP32 + DHT22 schematic design |
| `Lab Exersice using ESP32 - 2D.docx` | 2D layout documentation |
| `3D Lab Exersice using ESP32 File PCB .step` | 3D PCB design file (STEP format) |
| `Lab Exersice using ESP32.xlsx` | Component and specification spreadsheet |

---

## Part A — Circuit Calculations

### a) Series Circuit (20 Ω, 30 Ω, 50 Ω @ 125 V)
- Total resistance
- Total current
- Current through each resistor
- Voltage drop across each resistor
- Power dissipated by each resistor

### b) Parallel Circuit (20 Ω, 100 Ω, 50 Ω @ 125 V)
- Total resistance
- Total current
- Current through each resistor
- Voltage drop across each resistor
- Power dissipated by each resistor

> Full calculations and tables are available in `Part A.pdf`.

---

## Part B — ESP32 + DHT22 Schematic

A schematic diagram connecting an ESP32 microcontroller to a DHT22 temperature and humidity sensor. The DHT22 operates on a 3.3 V – 5 V supply.

### Components List

| Component | Quantity | Notes |
|-----------|----------|-------|
| ESP32 Dev Board | 1 | Main microcontroller |
| DHT22 Sensor | 1 | Temperature & humidity |
| Resistor (10 kΩ) | 1 | Pull-up on data line |
| Jumper Wires | — | Connections |
| Power Supply (3.3 V / 5 V) | 1 | Sensor supply |

> Full schematic is available in `Lab Exersice using ESP32 schematic.docx`.

---

## Tools Used

- **EasyEDA** — Schematic and PCB design
- **Microsoft Word / Excel** — Documentation
- **Git & GitHub** — Version control and submission

---

## How to View the Files

1. Clone the repository:
   ```bash
   git clone https://github.com/MawiraVictor/Circuit-Design-.git