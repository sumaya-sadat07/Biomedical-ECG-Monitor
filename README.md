# 🩺 Advanced Interactive ECG Signal Analyzer

An interactive, clinical-grade electrocardiogram (ECG) monitor and signal analyzer built with HTML5 Canvas and JavaScript. This project bridges **Biomedical Engineering (BME)** and frontend development, simulating real-time cardiac waveforms, clinical metrics, and diagnostic monitoring controls.

![Project Preview](https://img.shields.io/badge/Status-Active-brightgreen) ![Tech Stack](https://img.shields.io/badge/Tech-HTML5_%7C_CSS3_%7C_JavaScript-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)

---

## ✨ Key Features

* **Real-time CRT Scan Rendering:** Smooth, rolling electrocardiogram visual trace with dynamic grid alignment mimicking real ICU patient monitors.
* **Dynamic Clinical Metrics (PR & QT Intervals):** Mathematically recalculates PR intervals and QTc values in real-time as the heart rate changes based on medical formulas.
* **Interactive Controls & Heart Rate Adjustment:** 
  * Live **BPM Slider** (supports Bradycardia, Normal Sinus Rhythm, and Tachycardia classifications).
  * **Lead Configurations:** Switch between *Lead II (Standard)*, *Lead V1 (Right Ventricle)*, and *Arrhythmia Mode (PVCs)*.
* **Advanced Biomedical Simulations:**
  * **Noise & Artifacts Filter:** Toggle baseline wander and muscle jitter simulation.
  * **Web Audio API Beep Sound:** Real-time auditory feedback synced with R-peak crossings.
* **Signal Freeze / Analysis:** Pause the real-time wave to inspect specific cardiac cycles closely.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Graphics:** HTML5 Canvas 2D Context
* **Audio:** Web Audio API (Synthesized Beep Feedback)

---

## 🚀 Getting Started

To run this project locally, simply clone the repository and open the file in any modern web browser:

```bash
git clone [https://github.com/sumaya-sadat07/Biomedical-ECG-Monitor.git](https://github.com/sumaya-sadat07/Biomedical-ECG-Monitor.git)
