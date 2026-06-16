# HeartGlow

<div align="center">

<img src="Heartglow.png" alt="HeartGlow PCB" width="700"/>

### A Heart-Shaped LED PCB Designed to Celebrate Valentine's Day

HeartGlow is a compact heart-shaped electronic badge powered by a CR2032 coin cell and driven by a 555 timer oscillator. The board illuminates a series of LEDs arranged in a heart pattern, creating a visually appealing lighting effect suitable for gifts, decorative electronics, and PCB art projects.

</div>

---

# Overview

HeartGlow is a custom-designed PCB created as a themed electronics project that combines PCB design, schematic capture, and hardware prototyping.

The project demonstrates:

- PCB Design using KiCad
- LED array design
- 555 Timer oscillator implementation
- Coin-cell powered electronics
- PCB art and aesthetic routing
- Hardware prototyping and manufacturing workflow

---

# PCB Preview

## Top View

<img src="Heartglow.png" alt="HeartGlow PCB Layout" width="700"/>

## Circuit Schematic

<img src="Schematic1.png" alt="HeartGlow Schematic" width="900"/>

---

# Features

- Heart-shaped LED arrangement
- Battery powered using CR2032 coin cell
- NE555 timer based LED blinking circuit
- Compact and lightweight design
- Low component count
- Simple assembly process
- Designed entirely in KiCad

---

# Hardware Specifications

| Parameter | Value |
|------------|---------|
| Power Source | CR2032 Coin Cell |
| Timer IC | NE555 |
| LEDs | 14 Red LEDs |
| Switching Device | NPN Transistor |
| PCB Type | 2-Layer |
| CAD Software | KiCad |
| Control Method | 555 Timer Oscillator |

---

# Circuit Description

The design uses a classic NE555 timer configured in astable mode to generate a periodic output signal.

The timer output drives an NPN transistor that controls the LED array.

The blinking frequency is determined by:

- R1 = 4.7kΩ
- R2 = 47kΩ
- C1 = 10µF

The transistor provides sufficient current drive for the LED chain while maintaining low power consumption.

---

# Components Used

| Reference | Component |
|------------|------------|
| U1 | NE555 Timer |
| Q1 | NPN Transistor |
| BT1 | CR2032 Battery Holder |
| SW1 | SPDT Slide Switch |
| D1-D14 | Red LEDs |
| R1-R18 | Current Limiting & Timing Resistors |
| C1, C2 | Timing Capacitors |

---

# Design Goals

The project was designed to:

- Learn practical PCB design
- Explore timer-based LED circuits
- Create a themed electronics gift
- Gain experience in schematic capture and board layout
- Practice PCB manufacturing workflows

---

# Manufacturing Files

The repository contains:

- Gerber Files
- Drill Files
- PCB Images
- Schematic Documentation

These files can be directly uploaded to PCB manufacturers such as:

- JLCPCB
- PCBWay
- NextPCB
- OSH Park

---

# Tools Used

- KiCad
- Git
- GitHub

---

# Future Improvements

Potential upgrades include:

- Addressable RGB LEDs
- Multiple lighting patterns
- Rechargeable battery support
- Microcontroller-based animations
- USB-C charging

---

# License

This project is shared for educational and learning purposes.

---

<div align="center">

Designed with ❤️ using KiCad

</div>
