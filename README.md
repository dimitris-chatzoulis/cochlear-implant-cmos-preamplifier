# Low-Power, Low-Noise Preamplifier Front-End System for Cochlear Implants

This repository contains the main chapters of a thesis report titled:

**A Low-Power, Low-Noise Preamplifier for Cochlear Implants**  
**Author:** Dimitris Chatzoulis  
**Institution:** Aristotle University of Thessaloniki, School of Electrical and Computer Engineering  
**Academic Year:** 2024–2025

For the complete analysis refer to `Report.pdf`.

[View Report](./Report.pdf)

[view full-quality report on Gooogle Drive](https://drive.google.com/file/d/16PjLneQz6USgkRYqoxZL7kJiFPQ9ueV2/view?usp=drive_link)

## Brief Overview

* Developed a modified CMOS folded-cascode amplifier incorporating five analog design techniques into the conventional topology.
* Designed the biasing circuit, voltage reference, output filtering, and feedback network for the complete preamplifier analog front-end system.
* Performed schematic design, layout, and post-layout verification, including DRC, LVS, and parasitic extraction.
* Achieved 1.55 µW power consumption and 7.58 µVrms input-referred noise over 20 Hz–20 kHz, while validating gain, phase margin, PSRR, CMRR, THD, area, PVT corners, and temperature range.

## Preview

![Preamplifier schematic](figures/schematics_and_layout/preamplifier_schematic.png)

![Analog front-end layout](figures/schematics_and_layout/analog_front_end_layout.png)

![Gain-bandwidth with output filter](figures/simulation_results/gain_bandwidth_with_output_filter.png)

![Input-referred noise](figures/simulation_results/input_referred_noise.png)

![Performance comparison table](figures/performance_comparison_table.png)

## Repository Structure

```text
.
├── Report.pdf
└── figures/
    ├── schematics_and_layout/
    ├── simulation_results/
    └── performance_comparison_table.png
```

## Thesis Report

The full thesis is available through the Aristotle University of Thessaloniki Institutional Repository:
[https://ikee.lib.auth.gr/record/362517](https://ikee.lib.auth.gr/record/362517)

`Report.pdf` contains the main chapters of the thesis report. It provides the full explanation of the methodology, simulations, and conclusions.

In `Report.pdf` additional tables and simulations for process corners, harmonic distortion (THD), power consumption, temperature behavior, area, and comparison with similar amplifiers are included.

## Schematics and Layout

The `figures/schematics_and_layout/` folder contains the main schematic-level and layout-level figures of the analog front-end system:

* `preamplifier_schematic.png`
* `feedback_system_schematic.png`
* `bias_circuit_schematic.png`
* `reference_voltage_circuit_schematic.png`
* `analog_front_end_layout.png`

## Simulation Results

The `figures/simulation_results_/` folder contains the following simulation-result plots:

* `cmrr_layout_vs_schematic.png`
* `gain_bandwidth_without_output_filter.png`
* `gain_bandwidth_with_output_filter.png`
* `input_noise_layout_vs_schematic.png`
* `input_referred_noise.png`
* `phase_margin.png`
* `psrr_response.png`
* `vref_temperature_response.png`

## Note
Technology-specific implementation files are not included.

