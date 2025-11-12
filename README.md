# Audio Denoising Algorithms in MATLAB

This project demonstrates and compares several **audio denoising algorithms** implemented in MATLAB, including adaptive filtering and spectral methods. It supports white, colored, and tonal (hum) noise scenarios. Each technique produces a cleaned audio output and visualizes performance using plots and Mean Squared Error (MSE) comparisons.

---

## 🚀 Features

- **Adaptive Filters**
  - LMS (Least Mean Squares)
  - RLS (Recursive Least Squares)
- **Spectral Methods**
  - Spectral Subtraction
  - Ideal Wiener Filter
- **Noise Types**
  - White noise
  - Colored noise (low-pass)
  - Tonal noise (250 Hz hum)
- **Automatic Audio Generation**
  - If no input file is found, a synthetic test signal is generated.
- **Performance Comparison**
  - MSE-based evaluation across all filter–noise combinations.
  - Automated bar-plot visualization of denoising performance.

---

## 📂 File Outputs

Each method generates a cleaned audio file:
