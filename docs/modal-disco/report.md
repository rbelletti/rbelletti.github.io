[← Back to Showcase](../../index.html)

# Modal Testing

# 1. Introduction
This project focused on the experimental modal analysis of a floating brake disc through impact hammer testing and Frequency Response Function (FRF) measurements. The acquired data were processed in Siemens Testlab to identify the modal parameters governing the dynamic behavior of the structure, including natural frequencies, damping ratios, and mode shapes.

# 2. Experimental Setup
The experimental setup was designed to perform impact-based modal testing of a floating brake disc under free-free boundary conditions. To minimize the influence of external constraints, the disc was supported using soft foam elements with low energy absorption characteristics.

The structure was excited using an instrumented impact hammer, while the response was measured through a piezoelectric accelerometer sequentially positioned at different locations on the disc surface. Data acquisition and signal processing were performed using Siemens Testlab and Siemens acquisition hardware.

Before testing, the sensitivities of both transducers were calibrated within the Testlab channel setup to convert voltage signals into physical quantities.

| Hammer Sensitivity | Accelerometer Sensitivity |
| :--- | :--- |
| \\( 5.39 \cdot 10^{-3} \\) V/g (\\( g=9.81 \\) m/s²) | \\( 15.9 \cdot 10^{-3} \\) V/N |

The acquisition parameters - including bandwidth, spectral resolution, triggering conditions, windowing functions, and H1 FRF estimation - were selected to ensure accurate measurements while minimizing noise contamination.

![Figure 1 - Acquisition and FRF estimation settings](images/all_Settings.png)

***Figure 1** - Acquisition and FRF estimation settings used in Siemens Testlab (image used courtesy of Siemens Simcenter Testlab).*

Multiple impacts were acquired for each measurement point to improve repeatability and coherence quality. The accelerometer was mounted using beeswax to reduce mass-loading effects and allow rapid repositioning during the test campaign.

# 3. Measurement Procedure
The measurement campaign was conducted using a moving accelerometer approach. For each acquisition point, five impacts were recorded and averaged to improve signal quality and reduce random noise effects. A total of 84 Degrees of Freedom were acquired over the disc surface.

Measurement quality was evaluated through the coherence function, where values close to unity indicated reliable and repeatable measurements.

![Figure 2 - Coherence function](images/coherence.png)

***Figure 2** - Coherence function associated with the driving point FRF (image used courtesy of Siemens Simcenter Testlab).*

Local coherence reductions were observed near structural antiresonances, where the response amplitude becomes very small and measurement noise dominates the signal. The validity of the measurements was therefore assessed through combined analysis of FRF amplitude, phase, and PSD functions within Siemens Testlab.

![Figure 3 - Measurement interface](images/measurement_interface.png)

***Figure 3** - Measurement interface used during the impact testing campaign (image used courtesy of Siemens Simcenter Testlab).*

# 4. Modal Identification
The measured FRFs were post-processed in Siemens Testlab using a Multiple Degree of Freedom (MDOF) curve-fitting approach to extract the modal parameters of the brake disc.

Modal identification was performed through stabilization diagram analysis by progressively increasing the model order and monitoring pole stability across successive solutions. Poles showing stable frequency and damping values were identified as physical structural modes, while unstable poles were discarded as numerical artifacts.

![Figure 4 - Stabilization diagram](images/stabilization.png)

***Figure 4** - Stabilization diagram used for modal parameter identification (image used courtesy of Siemens Simcenter Testlab).*

Fourteen structural modes were successfully identified within the selected bandwidth. The reliability of the identified model was verified by comparing the measured FRFs with the reconstructed FRFs synthesized from the extracted modal parameters, showing good agreement over the analyzed frequency range.

# 5. Results
The modal identification procedure enabled the extraction of fourteen structural modes together with their corresponding natural frequencies and damping ratios.

The reconstructed FRFs showed good agreement with the experimental measurements in both amplitude and phase, confirming the reliability of the adopted MDOF fitting procedure. Minor discrepancies were mainly observed in antiresonance regions due to the low response amplitude and increased influence of measurement noise.

| Mode | Natural Frequencies [Hz] | Damping Ratio [%] |
| :--- | :--- | :--- |
| 1 | 12.2 | 4.56 |
| 2 | 161.6 | 0.13 |
| 3 | 343.0 | 0.10 |
| 4 | 403.1 | 0.05 |
| 5 | 414.0 | 0.04 |
| 6 | 639.7 | 0.11 |
| 7 | 650.6 | 0.10 |
| 8 | 745.1 | 0.04 |
| 9 | 1053.6 | 1.42 |
| 10 | 1108.0 | 0.35 |
| 11 | 1194.6 | 0.04 |
| 12 | 1382.9 | 0.64 |
| 13 | 1397.5 | 0.07 |
| 14 | 1526.0 | 0.30 |
