# Dual DC Power Supply Simulation

A comprehensive LTSpice simulation of a dual DC power supply designed to generate ±15.0V DC from a 120V (rms) AC residential voltage source operating at 60Hz.

## Project Overview

This project demonstrates the design and simulation of a dual DC power supply with the following features:
- Input: 120V (rms) AC at 60Hz
- Output: ±15.0V DC with ripple voltage ≤ 50mV
- Full-wave rectification using 1N4002 diodes
- Center-tapped transformer design
- Multi-stage filtering with capacitors (1000μF, 10μF, and 0.1μF)

## Technical Details

### Components
- AC Source: Single-phase 120V (rms) at 60Hz
- Center-Tapped Transformer:
  - Primary Inductance: 1mH
  - Secondary Leakage Inductances: 40μH each
- Rectification: 1N4002 diodes
- Filtering: Capacitor network (1000μF, 10μF, 0.1μF)

### Simulation Results
- Transformer turns ratio calculation
- Input and output voltage waveforms
- Ripple voltage analysis (maintained below 50mV)
- Diode current waveform analysis
- Transient response (stabilization time: ~9ms)

## Key Findings
- Transformer design sensitivity to secondary leakage inductances
- Impact of component selection on ripple voltage
- Trade-offs in power supply design
- Importance of simulation tools for circuit behavior prediction

## Simulation Environment
All simulations were conducted using LTSpice with detailed parameters captured in the report.

## Designed By
Chris Sam 