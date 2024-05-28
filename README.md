# Low Impedance Measurement Using Low Cost SDR VNA

## Overview

This project investigates low impedance measurements using a low-cost SDR VNA. It covers the need for low impedance measurement, two-port measurement methods, the lowest impedance measurable by the SDR VNA, RLC characteristics trends of circuit elements, and key takeaways.

## Need for Low Impedance Measurement

PDN components often have target impedances in the mOhm range, making it impractical to measure impedances less than 0.1 Ohms using return loss 1-port VNA. The 2-port method provides a low-cost solution to measure such low impedances.

## 4-Point Kelvin Method

The 4-point Kelvin method is used for accurate low impedance measurement. This setup helps in calculating the resistance accurately.

## 1 & 2 Port Methods

- **2-Port Method (Z < 0.1 Ohms):**
  ![2-Port Method](https://github.com/Shri2401/Low-Impedance-Measurement-Using-Low-Cost-SDR-VNA/blob/main/supporting%20pictures/port2.png)

- **1-Port Method (Z > 0.1 Ohms):**
  ![1-Port Method](https://github.com/Shri2401/Low-Impedance-Measurement-Using-Low-Cost-SDR-VNA/blob/main/supporting%20pictures/1port.png)

## SDR VNA Calibration

SDR VNA calibration involves open, short, load, and through measurements to ensure accurate impedance measurements.

## R & L Characteristics of SMT Resistors

The R and L characteristics of SMT resistors are modeled to understand their impedance behavior across different frequencies.

![R & L Characteristics of SMT Resistors](https://github.com/Shri2401/Low-Impedance-Measurement-Using-Low-Cost-SDR-VNA/blob/main/supporting%20pictures/Result.png)

## Lowest Impedance Measured by SDR VNA

The SDR VNA can measure very low impedances, down to the noise floor of the device.

![Lowest Impedance Measured by SDR VNA](images/lowest_impedance_measured.png)

## Takeaways

1. The 2-port method can eliminate the artifacts associated with contact impedance of the probes or fixturing to the DUT.
2. The 2-port method is a low-cost and reliable method for Low Z Measurement.
3. First order RL models can be used to hack the impedances measured with the 2-port method to correlate measured & simulated data.
4. SDR VNA can measure resistances & inductances in the mOhm and pH range respectively.
5. ESL of components depends on their footprint.

## Questions?

If you have any questions, please feel free to ask.
