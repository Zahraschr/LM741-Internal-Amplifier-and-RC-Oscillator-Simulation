## Project Overview
This project focuses on the analysis and simulation of the LM741 operational amplifier and the design of an RC relaxation oscillator circuit in software.

## Part 1 — LM741 Internal Structure Simulation
- The internal schematic of LM741 is recreated based on its datasheet.
- Differential amplifier stage, active load, and output power amplifier are modeled.
- Key characteristics such as differential gain, input stage behavior, and output driving capability are observed.

## Part 2 — RC Relaxation Oscillator and Integrator
- A comparator-based RC oscillator is designed to generate a square-wave signal.
- The output signal is passed through an op-amp integrator to form a triangular waveform.
- The frequency of oscillation is calculated using:
  f = 1 / (2 * R * C * ln((1 + k) / (1 - k)))
  where k = R2 / (R1 + R2)

## Results
- The internal LM741 amplifier model demonstrates correct multi-stage analog amplification behavior.
- The RC oscillator successfully produces a stable square wave, and the integrator outputs a smooth triangular waveform.
