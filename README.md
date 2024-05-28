# Low Impedance Measurement Using Low Cost SDR VNA

## Overview

This project investigates low impedance measurements using a low-cost SDR VNA. It covers the need for low impedance measurement, two-port measurement methods, the lowest impedance measurable by the SDR VNA, RLC characteristics trends of circuit elements, and key takeaways.

## Need for Low Impedance Measurement

PDN components often have target impedances in the mOhm range, making it impractical to measure impedances less than 0.1 Ohms using return loss 1-port VNA. The 2-port method provides a low-cost solution to measure such low impedances.

## 4-Point Kelvin Method

The 4-point Kelvin method is used for accurate low impedance measurement. This setup helps in calculating the resistance accurately.

## 1 & 2 Port Methods

- **2-Port Method (Z < 0.1 Ohms):**
  ![2-Port Method](images/2_port_method.png)

- **1-Port Method (Z > 0.1 Ohms):**
  ![1-Port Method](images/1_port_method.png)

## SDR VNA Calibration

SDR VNA calibration involves open, short, load, and through measurements to ensure accurate impedance measurements.

![SDR VNA Calibration](images/sdr_vna_calibration.png)

## Correlation in Measured & Simulated Resistor Impedance

Comparing the measured and simulated impedance of resistors helps validate the measurement accuracy.

![Correlation in Measured & Simulated Resistor Impedance](images/correlation_measured_simulated.png)

## R & L Characteristics of SMT Resistors

The R and L characteristics of SMT resistors are modeled to understand their impedance behavior across different frequencies.

![R & L Characteristics of SMT Resistors](images/r_l_characteristics_smt_resistors.png)

## Lowest Impedance Measured by SDR VNA

The SDR VNA can measure very low impedances, down to the noise floor of the device.

![Lowest Impedance Measured by SDR VNA](images/lowest_impedance_measured.png)

## RLC Equivalent Z for Capacitors

Examining the RLC equivalent impedance for different types of capacitors, such as MLCC, electrolytic, and tantalum capacitors.

![RLC Equivalent Z for Capacitors](images/rlc_equivalent_z_capacitors.png)

## ESL of MLCC with Different Via Positions

The equivalent series inductance (ESL) of MLCCs varies with the via position, affecting t
