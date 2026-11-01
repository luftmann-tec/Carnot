# Carnot in Motion: A Time-Dependent Simulation with MATLAB

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23850214.svg)]([https://doi.org/TU-DOI](https://doi.org/10.5281/zenodo.23850214))
[![View Carnot in Motion: A Time-Dependent Simulation with MATLAB on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://la.mathworks.com/matlabcentral/fileexchange/185124-carnot-in-motion-a-time-dependent-simulation-with-matlab)
[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=luftmann-tec/Carnot)

**Author:** Prof. Rodolfo Salazar  
**Affiliation:** Tecnológico de Monterrey, Campus Guadalajara, Mexico  
**Event:** 2026 MATLAB STEM Showcase

## Overview

Thermodynamics is often introduced through equilibrium states and state diagrams, which may lead students to perceive it as a predominantly static discipline.

This educational activity explores a different perspective by explicitly introducing time into the classical Carnot cycle through MATLAB. An ideal gas undergoes the four reversible processes of the cycle while its volume is defined as a periodic function of time.

The simulation calculates the corresponding pressure evolution, displays the system's behavior through time-dependent plots and the conventional pressure-volume (P-V) diagram, and uses numerical integration to determine the work transferred throughout successive cycles.

By connecting thermodynamic states, process trajectories, and cumulative work, this activity provides an intuitive way to explore energy conversion and the dynamic interpretation of a classical thermodynamic cycle.

## Learning Objectives

By completing this activity, students will be able to:

- Identify and describe the four thermodynamic processes of the Carnot cycle.
- Understand how a periodic volume function can represent the temporal evolution of a thermodynamic system.
- Visualize pressure and volume changes as functions of time.
- Interpret the Carnot cycle using both time-dependent plots and a P-V diagram.
- Calculate cumulative work through numerical integration.
- Relate operating temperatures to the theoretical Carnot efficiency.

## Requirements

- MATLAB.
- Basic knowledge of thermodynamics, particularly ideal gases and the Carnot cycle.
- Familiarity with MATLAB fundamentals is recommended.

No additional toolboxes are required for the basic implementation.

## System Description

The simulation considers an ideal monoatomic gas confined in a piston-cylinder system. The gas undergoes the four reversible processes that constitute the Carnot cycle:

1. Isothermal expansion at the hot-reservoir temperature.
2. Adiabatic expansion.
3. Isothermal compression at the cold-reservoir temperature.
4. Adiabatic compression.

The volume is prescribed as a periodic function of time, allowing successive cycles to be represented and analyzed.

**Model scope:** This is a time-parameterized representation of an idealized reversible Carnot cycle. It does not solve the mechanical dynamics of the piston or the actual heat-transfer rates between the gas and its surroundings.

## Simulation Features

The MATLAB implementation includes:

- Time-dependent volume and pressure profiles.
- A conventional pressure-volume diagram.
- Identification of the four thermodynamic states.
- Numerical integration of pressure with respect to volume to calculate work.
- Visualization of cumulative work over successive cycles.
- Calculation of theoretical Carnot efficiency.
- Parameters that can be modified to explore different operating conditions.

## Getting Started

1. Download or clone the repository.
2. Open the MATLAB Live Script (`.mlx`).
3. Run the sections sequentially.
4. Review the introductory material on entropy.
5. Execute the simulation and examine the resulting plots.
6. Modify the parameters and explore how the system responds.

## Suggested Exploration

Students are encouraged to investigate the following questions:

- How does the number of cycles affect cumulative work?
- What happens when the hot- and cold-reservoir temperatures change?
- How do the operating volumes influence the cycle and its efficiency?
- Why does cumulative work increase after each completed cycle?
- If the volume follows a different periodic function while preserving the same thermodynamic states, does the net work per cycle change?
- How does the numerical result compare with the theoretical work calculated from the thermodynamic relationships?

## Educational Context

This activity emphasizes the distinction between describing a thermodynamic system through equilibrium states and representing the temporal evolution of its processes.

By incorporating time explicitly, students can visualize not only the closed trajectory of a Carnot cycle in a P-V diagram but also how work is transferred and accumulated as the cycle repeats.

The activity is intended to support active learning through computational experimentation, visualization, and guided inquiry.

## References

- Çengel, Y. A., & Boles, M. A. (2011). *Thermodynamics: An Engineering Approach*. McGraw-Hill.
- Levine, I. N. (1988). *Physical Chemistry*. McGraw-Hill.
- Wolfram Research. Wolfram Demonstrations Project: Thermodynamics resources.

## License

Specify the license under which this material is distributed.

## Acknowledgments

Developed using MATLAB as an educational resource for engineering thermodynamics.
