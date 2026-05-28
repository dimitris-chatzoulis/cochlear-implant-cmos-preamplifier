# Low-Power, Low-Noise Preamplifier Front-End System for Cochlear Implants

This repository contains the main chapters of a thesis report titled:

**A Low-Power, Low-Noise Preamplifier for Cochlear Implants**  
**Author:** Dimitris Chatzoulis  
**Institution:** Aristotle University of Thessaloniki, School of Electrical and Computer Engineering  
**Academic Year:** 2024–2025

The full thesis is available through the Aristotle University of Thessaloniki Institutional Repository:

[https://ikee.lib.auth.gr/record/362517](https://ikee.lib.auth.gr/record/362517)

## Brief Overview

* Developed a modified CMOS folded-cascode amplifier incorporating five analog design techniques into the conventional topology.
* Designed the biasing circuit, voltage reference, output filtering, and feedback network for the complete preamplifier analog front-end system.
* Performed schematic design, layout, and post-layout verification, including DRC, LVS, and parasitic extraction.
* Achieved 1.55 µW power consumption and 7.58 µVrms input-referred noise over 20 Hz–20 kHz, while validating gain, phase margin, PSRR, CMRR, THD, area, PVT corners, and temperature range.

## Repository Structure

```text
.
├── Thesis_Report.pdf
└── figures/
    ├── schematics\_and\_layout/
    └── simulation\_results/
```

## Thesis Report

`Thesis_Report.pdf` contains the main chapters of the thesis report. It provides the full explanation of the methodology, simulations, and conclusions.

In `Thesis_Report.pdf` additional tables and simulations for process corners, harmonic distortion (THD), power consumption, temperature behavior, area, and comparison with similar amplifiers are included.

## Schematics and Layout

The `figures/schematics\_and\_layout/` folder contains the main schematic-level and layout-level figures of the analog front-end system:

* `preamplifier\_schematic.png`
* `feedback\_system\_schematic.png`
* `bias\_circuit\_schematic.png`
* `reference\_voltage\_circuit\_schematic.png`
* `analog\_front\_end\_layout.png`

## Simulation Results

The `figures/simulation\_results/` folder contains the following simulation-result plots:

* `cmrr\_layout\_vs\_schematic.png`
* `gain\_bandwidth\_without\_output\_filter.png`
* `gain\_bandwidth\_with\_output\_filter.png`
* `input\_noise\_layout\_vs\_schematic.png`
* `input\_referred\_noise.png`
* `phase\_margin.png`
* `psrr\_response.png`
* `vref\_temperature\_response.png`

## Note

For the complete analysis refer to `Thesis\_Report.pdf`.
Technology-specific implementation files are not included.

