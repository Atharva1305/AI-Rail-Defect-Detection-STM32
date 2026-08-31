# AI-Based Acoustic Wave Monitoring System for Rail Defect Detection

A low-cost **STM32-based intelligent railway monitoring system** that detects rail defects using vibration and acoustic signals with **Signal Processing** and **Machine Learning**.

## Project Overview

Railway tracks develop cracks and wear due to continuous mechanical stress. This project captures vibration signals using **MPU6050** and **Piezoelectric Sensors**, processes them using **STM32**, extracts frequency-domain features through **FFT**, and classifies rail health using Machine Learning.

## Features

* Real-time vibration monitoring
* STM32-based data acquisition
* FFT signal processing
* Feature extraction
* AI-based defect classification
* OLED status display
* Dashboard visualization
* Predictive maintenance approach

## Hardware

| Component             | Purpose                           |
| --------------------- | --------------------------------- |
| STM32 Black Pill/F411 | Main Controller                   |
| MPU6050               | 3-axis vibration sensing          |
| Piezo Sensor          | Crack-sensitive vibration sensing |
| OLED                  | Status display                    |
| Buzzer                | Alert                             |
| MicroSD               | Data logging                      |

## Software Stack

* STM32CubeIDE
* CMSIS-DSP
* Python
* TensorFlow
* Scikit-learn
* Streamlit
* Jupyter Notebook

## System Architecture

Rail → Sensors → STM32 → FFT → Feature Extraction → Machine Learning → Dashboard → Alert

## Project Status

* [x] Literature Review
* [x] System Architecture
* [x] Hardware Selection
* [ ] STM32 Firmware
* [ ] Dataset Collection
* [ ] AI Model Training
* [ ] Dashboard Integration
* [ ] Prototype Testing

## Team

* Atharva Bhagwat
* Payal Kainge

## License

MIT License
