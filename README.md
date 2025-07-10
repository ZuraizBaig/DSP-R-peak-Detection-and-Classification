# 🫀 R-Peak Detection using Digital Signal Processing (DSP)

This repository contains a Jupyter Notebook (`DSP_and_R_Peak.ipynb`) demonstrating how to apply digital signal processing (DSP) techniques to electrocardiogram (ECG) signals in order to accurately detect **R-peaks**.

---

## 📘 Notebook Overview

The notebook covers the following steps:

- 📥 Loading and visualizing raw ECG data  
- 🧹 Preprocessing using band-pass filtering (e.g., Butterworth)  
- ➕ Signal transformation using:
  - Derivative operation
  - Squaring
  - Moving window integration  
- 📈 R-peak detection using `scipy.signal.find_peaks`  
- 📊 Plotting detected R-peaks on ECG waveforms for visual verification  

---

## 🧰 Requirements

Install the following Python libraries before running the notebook:

```bash
pip install numpy scipy matplotlib
