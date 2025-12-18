# Vehicle Control Unit (VCU) for 3-in-1 E-Axle

## Overview
This repository presents the design, simulation, and prototype-level implementation of a
Vehicle Control Unit (VCU) developed for a three-in-one E-Axle system in electric vehicles.

The work focuses on generating a controlled three-phase sinusoidal output using
SPWM techniques for motor speed and torque control.

> ⚠️ Note: This repository contains **summarized technical knowledge and implementation insights**.
> The complete academic report is shared **on request** via a private drive link.

## Key Contributions
- Multi-stage VCU design evolution (4 approaches)
- SPWM-based inverter control
- Three-phase output generation
- MATLAB & Proteus validation
- Hardware prototype testing

## Tools & Technologies
- MATLAB / Simulink
- Proteus Design Suite
- Arduino (UNO / Nano)
- MOSFETs & IGBTs
- RC Signal Conditioning Filters

## Repository Structure
docs/        → Concept & system explanation
hardware/    → Hardware design insights
software/    → Control logic & firmware description
simulation/  → Simulation methodology & results
research/    → Literature insights & references
images/      → Diagrams & waveforms


---

# 📘 STEP 4: docs/ (EXTRACTED KNOWLEDGE)

### `docs/README.md`
```md
# System Documentation

## Problem Statement
Electric vehicles require compact, efficient, and scalable drive systems.
Traditional separated motor, inverter, and transmission designs increase
cost, complexity, and losses.

## Proposed Solution
A Vehicle Control Unit (VCU) designed for a three-in-one E-Axle system,
capable of controlling motor speed and torque via controlled frequency
and voltage modulation.

## Objectives
- Compact integration of motor control electronics
- Cost-effective prototype development
- Scalable control architecture
- High efficiency through PWM-based control
