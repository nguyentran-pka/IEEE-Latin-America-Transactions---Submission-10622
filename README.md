# IEEE-Latin-America-Transactions---Submission-10622
# A Simple Patch Antenna Design with Multiple Linear Polarizations for RFID Readers

This repository contains the simulation models and data for the antenna presented in the paper "A Simple Patch Antenna Design with Multiple Linear Polarizations for RFID Readers". The proposed design features a compact, polarization-reconfigurable antenna optimized for Ultra-High Frequency (UHF) RFID applications.

## 1. Overview
This research introduces a simple yet robust mechanism to switch between four linear polarization states, minimizing polarization mismatch in complex RFID environments. The design is based on:
* **Reconfigurable Feeding Network:** A one-to-three power divider network printed on the underside of the substrate.
* **Simplified Switching:** Uses only three PIN diodes (MACOM MADP-042305-130600) to achieve four polarization modes.
* **Polarization States:** Capable of generating Horizontal, Vertical, and two Diagonal ($+45^{\circ}$ and $-45^{\circ}$) linear polarizations.
* **Main Radiator:** A crossed-patch structure excited by different feeding positions (F-1, F-2, and F-3) to adjust current flow.

## 2. Design Specifications
The antenna is constructed using a low-cost multilayer configuration:
* **Substrates:** Two layers of FR-4 separated by an air gap.
* **Dielectric Constant ($\epsilon_r$):** 4.4.
* **Loss Tangent ($\tan \delta$):** 0.02.
* **Overall Dimensions:** $0.67\lambda \times 0.67\lambda \times 0.04\lambda$ at 915 MHz.
* **Physical Size:** $220 \times 220 \times 11.6$ mm³.
* **Center Frequency:** 915 MHz.

## 3. Performance Summary
Experimental and simulation results confirm high radiation efficiency and stable performance:
* **Common Operating Bandwidth:** 910 MHz to 925 MHz ($|S_{11}| < -10$ dB).
* **Broadside Realized Gain:** Better than 6.2 dBi for all polarization modes within the operating band.
* **Peak Gain:** Approximately 6.9–7.0 dBi achieved in diagonal modes.
* **Polarization Isolation:** Exceeds 15 dB between co-polarized and cross-polarized components.
* **Front-to-Back Ratio:** Greater than 15 dB for all states.

## 4. Repository Structure
* `/HFSS_Models`: Contains `.aedt` files for the proposed crossed-patch antenna and the reconfigurable feeding network.
* `/Simulation_Data`: Raw `.csv` and `.txt` files for reflection coefficients ($|S_{11}|$) and gain patterns.
* `/Measurement_Results`: Fabricated prototype data validated using a Vector Network Analyzer and anechoic chamber.

## 5. Applications
The antenna is specifically designed for UHF RFID reader systems where orientation robustness is critical:
* **Handheld RFID Readers:** Compact form factor suitable for mobile devices.
* **Warehouse & Logistics:** Reliable tag detection regardless of random tag orientations.
* **Multi-tag Environments:** Enhanced reading range and reduced hardware complexity.

## 6. License
