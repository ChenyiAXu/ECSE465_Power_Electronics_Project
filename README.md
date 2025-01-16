# Simulation and Analysis of a Bidirectional AC-DC and DC/DC Converter for V2G Applications

## Overview

This project focuses on the design, simulation, and analysis of a **bidirectional energy transfer system** utilizing:
1. A **single-phase bidirectional AC-DC converter**.
2. A **bidirectional DC-DC converter**.

The system enables energy flow between the grid and an electric vehicle (EV) battery, facilitating:
- **Grid-to-Vehicle (G2V):** Charging the EV battery from the grid.
- **Vehicle-to-Grid (V2G):** Discharging the battery to supply energy back to the grid.

The results demonstrate enhanced energy efficiency, grid stability, and economic feasibility for integrating EVs into sustainable energy systems.

---

## Key Features

- **Bidirectional Energy Flow**: Supports both charging (G2V) and discharging (V2G) operations.
- **Improved Grid Power Factor**: Ensures efficient grid interaction.
- **Economic Value**: Reduces utility load during peak hours and provides financial incentives for EV owners.
- **Simulation-Driven Design**: Validated using Electromagnetic Transients Program (EMTP) simulations.
- **Robust Control Mechanism**: Employs Proportional-Integral (PI) control for precise operation.

---

## System Configuration

1. **AC-DC Converter**:
   - Converts 230V, 60Hz AC supply to 380V DC.
   - Equipped with an LCL filter to minimize high-frequency harmonics.

2. **DC-DC Converter**:
   - A bidirectional buck-boost configuration regulates energy flow to/from the battery.
   - Operates in:
     - **Buck Mode** (charging): Steps down voltage for battery charging.
     - **Boost Mode** (discharging): Steps up voltage for supplying energy to the grid.

3. **Battery Storage**:
   - Modeled using a Thevenin equivalent circuit for accurate performance simulation.
   - Rated at 1.2 kW charging power and 120 V voltage.

---

## Simulation Highlights

- **Control Strategies**: Implements a PI controller with PWM for efficient switching and voltage regulation.
- **Performance Metrics**:
  - Stable grid voltage during mode transitions.
  - Low Total Harmonic Distortion (THD) for grid current (<6.3%).
  - Smooth DC bus voltage and battery voltage waveforms.

---

## Results

- **Energy Efficiency**: Achieved efficient energy transfer with minimal losses.
- **Grid Stability**: Maintained operational voltage and current quality.
- **Economic and Technical Feasibility**: Demonstrated readiness for real-world applications.

---
