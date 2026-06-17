# RESCUE-AR: Responsive Sensor-Fusion for Civil-Protection and Disaster Response Using Mobile Augmented Reality

This repository contains the conceptual framework, mathematical architecture artifacts, and evaluation datasets for **RESCUE-AR**, a mobile Augmented Reality (AR) and adaptive sensor-fusion framework designed for first responders in disaster response and civil protection environments.

## Overview

RESCUE-AR addresses the challenge of positioning and situational awareness degradation in extreme environments (e.g., smoke, structural collapse, GNSS-denied areas) by introducing an adaptive, multi-sensor measurement fusion strategy that dynamically weights Visual SLAM, IMU, depth sensing, and GNSS data.

## Repository Structure

* `/data`: Contains the anonymized survey and questionnaire responses from the user-centered evaluation ($n=19$, divided into Operational and Academic groups).
* `/docs`: Supplementary documentation regarding the mathematical model formalization ($$\phi_{V-SLAM}(\Lambda_k)$$) and architectural blocks.

## Evaluation Methodology & Questionnaires

The user-centered validation evaluated:
1.  **System Usability Scale (SUS)**
2.  **NASA Task Load Index (NASA-TLX)** for anticipated cognitive and physical workload.
3.  **Core Concept & Operational Suitability** (Trust, data accuracy confidence, and visual annotation utility).

The raw, anonymized datasets can be found in the following files:
* `data/evaluation_responses.csv`: Contains the survey and questionnaire responses from the user-centered evaluation ($$n=19$$, divided into Operational and Academic groups).
* `data/sensor_fusion_metrics.csv`: Numerical data and sensor behavior parameters under the simulated disaster use cases (e.g., variable visual features $$N_f$$, GNSS degradation).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Citation

If you use this framework or dataset in your academic work, please cite our paper:
*(Citation details will be updated upon journal publication)*
