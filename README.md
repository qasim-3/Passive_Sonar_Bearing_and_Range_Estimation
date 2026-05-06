# Passive Sonar Bearing and Range Estimation System

A real-time Digital Signal Processing (DSP) simulation engineered in MATLAB to detect, track, and locate multiple moving targets in an underwater environment using acoustic signatures.

## Core Technical Implementations

* **Delay-and-Sum Beamforming:** Implemented a real-time spatial filtering algorithm across a simulated 8-sensor Linear Hydrophone Array to accurately estimate target bearing (direction) by calculating constructive and destructive interference.
* **Spectral Isolation:** Utilized 4th-Order Butterworth Bandpass Filters to cleanly separate overlapping acoustic frequencies (e.g., 400Hz turbine whine vs. 800Hz active pings), isolating distinct targets from the ocean noise floor.
* **Range Estimation:** Engineered a physics-based attenuation model utilizing the Inverse Square Law of transmission loss to calculate target distance dynamically based on raw received power.
* **Live GUI Visualization:** Built a dynamic graphical interface featuring a simulated Radar/Polar display, real-time ground-truth tracking, and a beamformer spectrum plot to verify calculations.

## Technologies Used
* **Language:** MATLAB
* **Domain:** Digital Signal Processing (DSP), Array Signal Processing, Acoustics

## Repository Contents
* `Passive_Sonar_Bearing_and_Range_Estimation.m`: The complete MATLAB source code containing the physics engine, beamforming algorithms, and GUI generation.
* `Passive_Sonar_Bearing_and_Range_Estimation_Report.pdf`: Comprehensive project documentation, including mathematical methodologies, array geometry formulas, and output visualizations.
