# KiCad Projects

A collection of custom PCB designs created in KiCad for various electronics projects.

## Projects

### � [Project Lux - Free-Space Optical Audio Link](./FSO/)
A laser-based audio communication system developed for the Howard University **IEEE H.O.P.E. (Hands-On PCB Engineering)** Project (Fall 2025). This sophisticated project demonstrates optical communication principles by transmitting high-fidelity audio over a laser beam.

#### [Transmitter Board](./FSO/Transmitter%20board/)
Modulates a 3.5mm audio input signal onto a laser diode using a transconductance stage with op-amps and transistors.

#### [Receiver Board](./FSO/Receiver%20board/)
Uses **BPW34** photodiodes with a transimpedance amplifier (TIA), voltage pre-amplification via **LM358**, and a **PAM8403D** Class-D audio amplifier to drive speakers.

---

### �🔊 [Audio Amplifier](./audio_amplifier/)
A low voltage audio power amplifier board based on the **LM386** IC. Perfect for small speaker applications requiring simple audio amplification from line-level sources.

### 📡 [Proximity Sensor](./proximity_sensor/)
An LED bar graph display board using the **LM3914** dot/bar display driver. Provides a visual representation of an analog signal level through a 10-LED bar graph display.

### 🤖 Recyclobot System
The Recyclobot is a robotics project consisting of two main PCBs:

#### [Controller](./recyclobot/controller/)
An RF remote control encoder board using the **HT12E** serial encoder IC. This board encodes button presses and transmits commands wirelessly to the motherboard.

#### [Motherboard](./recyclobot/motherboard/)
The main control board for the Recyclobot, featuring an **L293D** quadruple half-H motor driver. Receives wireless commands and controls DC motors for robot movement.

---

## Directory Structure

```
kicad-projects/
├── FSO/                 # Project Lux - Free-space optical audio link
│   ├── Receiver board/  # Photodiode array + TIA + audio amp
│   └── Transmitter board/ # Laser modulation circuit
├── audio_amplifier/     # LM386 audio amplifier board
├── proximity_sensor/    # LM3914 LED bar graph display
└── recyclobot/
    ├── controller/      # HT12E RF remote encoder
    └── motherboard/     # L293D motor driver board
```

## Getting Started

Each project directory contains:
- `.kicad_sch` - Schematic file
- `.kicad_pcb` - PCB layout file
- `.kicad_pro` - Project file
- `board.png` - Visual preview of the PCB design
- `gerbers/` - Manufacturing files (where available)

Open the `.kicad_pro` file in KiCad 8.0 or later to view and edit the designs.

## License

Personal electronics projects.
