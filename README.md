# Advanced Interactive ECG Signal Analyzer

An interactive, clinical-grade electrocardiogram (ECG) monitor and signal analyzer built with HTML5 Canvas and JavaScript. This project bridges Biomedical Engineering and frontend development by simulating real-time cardiac waveforms, clinical metrics, and diagnostic monitoring controls.

## Live Demo
You can view and test the live application here: [Biomedical ECG Monitor Live](https://sumaya-sadat07.github.io/Biomedical-ECG-Monitor/)

## Description
The application functions as a web-based biomedical monitoring device that renders smooth, rolling ECG traces with dynamic grid alignment. It dynamically calculates medical metrics and allows users to simulate various cardiac states and signal filtering options directly in the browser.

## Key Features
- **Real-Time CRT Scan Rendering:** Smooth, rolling electrocardiogram visual trace mimicking real ICU patient monitors.
- **Dynamic Clinical Metrics:** Automatically recalculates PR intervals and QTc values in real-time as the heart rate changes.
- **Interactive Controls & Heart Rate Adjustment:** Live BPM slider supporting Bradycardia, Normal Sinus Rhythm, and Tachycardia classifications.
- **Lead Configurations:** Switch between Lead II (Standard), Lead V1 (Right Ventricle), and Arrhythmia Mode (PVCs).
- **Noise & Artifacts Filter:** Toggle baseline wander and muscle jitter simulation for clinical realism.
- **Web Audio API Beep Sound:** Real-time auditory feedback synced with R-peak crossings.
- **Signal Freeze:** Pause the real-time wave to inspect specific cardiac cycles closely.

## Tech Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Graphics:** HTML5 Canvas 2D Context
- **Audio:** Web Audio API

git clone [https://sumaya-sadat07.github.io/Biomedical-ECG-Monitor.git](https://sumaya-sadat07.github.io/Biomedical-ECG-Monitor.git)
