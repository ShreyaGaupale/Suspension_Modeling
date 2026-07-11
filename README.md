## Overview

This repository presents a comprehensive study of a single-stage pendulum suspension, combining analytical modeling, experimental characterization, and thermal noise analysis. An analytical model of the suspension was developed using Lagrangian formalism and state-space modeling to investigate its dynamic behaviour and resonance characteristics. The theoretical predictions were validated through experimental modal analysis, where the resonance frequencies and quality factors of the pendulum modes were determined from measured data. Finally, the experimentally extracted parameters were used to investigate the thermal noise behaviour of the suspension, providing a complete workflow from theoretical modeling and experimental validation to noise analysis.


## Scientific Motivation

Gravitational waves provide a unique window into the universe, enabling the study of phenomena such as black hole mergers, neutron star collisions, and the validation of general relativity. However, by the time these waves reach the Earth, they produce displacements as small as 10⁻¹⁸ m. In contrast, ambient seismic activity generates ground vibrations at a magnitude of approximately 10⁻⁷ m, presenting a significant signal-to-noise challenge. Therefore, detecting such faint signals requires exceptional vibration isolation to prevent environmental disturbances from overwhelming the gravitational-wave signal.

Mechanical oscillators naturally attenuate vibrations above their resonance frequency, making them highly effective vibration isolators. Consequently, modern gravitational-wave interferometers suspend their mirrors using multi-stage pendulum systems, which progressively reduce the transmission of seismic vibrations. Understanding the dynamic behaviour, resonance characteristics, and thermal noise performance of these suspension systems is therefore essential for improving detector sensitivity. This project contributes to that understanding through the analytical modeling, experimental characterization, and thermal noise analysis of a single-stage pendulum suspension.


## Objectives

The primary objectives of this project are to:

* Develop analytical models of the six degrees of freedom of a single-stage pendulum suspension by deriving the equations of motion using Lagrangian formalism.
* Implement the analytical model through state-space modeling to obtain the transfer functions, dynamic response, and resonance characteristics of the suspension.
* Experimentally characterize the suspension by estimating the resonance frequencies and quality factors of its modes.
* Validate the analytical model through comparison with experimental measurements.
* Investigate the thermal noise behaviour of the suspension using experimentally determined parameters.
* Demonstrate the principles of vibration isolation employed in precision interferometric experiments such as gravitational-wave detectors.


## Repository Structure

### 1. Damped Oscillator Analysis
The damped harmonic oscillator forms the foundation of vibration isolation systems. This section investigates the behaviour of oscillators in both the time and frequency domains to understand how different damping mechanisms influence resonance, dynamic response, and vibration isolation.

#### Time-Domain Analysis
The time-domain response of both undamped and damped harmonic oscillators was studied to understand the effect of damping on the system dynamics. The following cases were investigated:

* Simple Harmonic Oscillator (No Damping)
* Underdamped Oscillator
* Critically Damped Oscillator
* Overdamped Oscillator

The displacement response of each damping regime was analyzed and compared to illustrate the influence of damping on the motion of the oscillator.

#### Frequency-Domain Analysis
The analysis was then extended to the frequency domain using transfer functions to characterize the response of vibration isolators. Three damping models were investigated:

* Undamped Oscillator
* Velocity Damping
* Internal Friction Damping

These concepts provide the theoretical foundation for the analytical modeling of the pendulum suspension presented in the subsequent sections.
  
### 2. Analytical Modeling
This section presents the analytical modeling of a single-stage, four-wire pendulum suspension system to investigate the dynamic behaviour of its six degrees of freedom. The equations of motion were derived using **Lagrangian formalism** and implemented through **state-space modeling** to characterize the response of the suspension.

The suspension system was modeled for the following modes:

* Vertical
* Longitudinal & Pitch (Coupled)
* Transverse & Roll (Coupled)
* Yaw

For each mode, the state-space representation was used to:

* Generate the transfer functions of the suspension.
* Obtain the corresponding Bode magnitude and phase plots.
* Calculate the resonance frequencies from the eigenvalues of the system matrix.
* Verify the analytically calculated resonance frequencies using the resonance peaks in the transfer function magnitude plots.

The analytical model provides a theoretical description of the suspension dynamics and serves as the basis for comparison with the experimentally measured response presented in the following section.



## Methodology

## Key Results

## Tools and Libraries

## Thesis
