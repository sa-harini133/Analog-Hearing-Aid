# Analog-Hearing-Aid


## Overview

A low-cost analog hearing aid designed to amplify weak audio signals for individuals with mild to moderate hearing loss. The project implements a multi-stage transistor amplifier with automatic level control, volume adjustment, and noise reduction. The hardware prototype was built on a general-purpose breadboard/perfboard and verified through LTspice simulation.

---

## Features

* Multi-stage audio amplification
* Automatic Level Control (ALC)
* Adjustable volume control
* Noise reduction circuitry
* Low-power analog design
* LTspice simulation
* Breadboard/perfboard hardware prototype

---

## System Architecture

```text
Microphone
     │
     ▼
Pre-Amplifier
     │
     ▼
Automatic Level Control
     │
     ▼
Volume Control
     │
     ▼
Power Amplifier
     │
     ▼
Headphone Output
```

---

## Components Used

* Condenser Microphone
* BC547 NPN Transistors
* BC337 Transistor
* Resistors
* Capacitors
* 1N4148 Diode
* Variable Resistor (Potentiometer)
* Audio Jack
* Battery

---

## Working Principle

The microphone converts sound into electrical signals, which are amplified through two transistor-based preamplifier stages. An Automatic Level Control (ALC) circuit regulates amplification based on input signal strength, preventing excessive output levels. The processed signal is then amplified by the output stage and delivered to headphones through an adjustable volume control.

---

## Simulation

The complete circuit was designed and validated using **LTspice** before hardware implementation to verify amplification and overall circuit performance.

---

## Hardware Prototype

The hearing aid was assembled and tested on a **general-purpose breadboard/perfboard** using discrete electronic components. Functional testing demonstrated successful audio amplification with adjustable gain and stable circuit operation.

---

## Technologies Used

* Analog Electronics
* LTspice
* Audio Signal Amplification
* Circuit Design
* Breadboard/Perfboard Prototyping

---

## Applications

* Hearing assistance devices
* Analog audio amplification
* Educational electronics projects
* Low-cost assistive technology

---

## Future Improvements

* Digital signal processing (DSP)
* Adaptive noise cancellation
* Bluetooth connectivity
* Rechargeable power supply
* Miniaturized PCB implementation
* AI-assisted adaptive hearing profiles

---

## Repository Structure

```text
.
├── LTspice/
├── Circuit_Diagram/
├── Hardware/
├── Images/
├── Documentation/
└── README.md
```

---

## Results

* Successfully designed and simulated the analog hearing aid circuit.
* Built and tested a working hardware prototype on a breadboard/perfboard.
* Achieved clear amplification of low-level audio signals with adjustable output volume.
* Demonstrated an affordable analog solution for basic hearing assistance.

---

## Contributors

* S. A. Harini
* Mirunalini A.
* S. Deepika Sri
* Samyukta Srikanth
* Aarush Jagannathan
