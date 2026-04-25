# Interactive Line Coding Visualizer
**A Comprehensive Tool for Digital Communications & Baseband Signaling**

Developed by: **Mohammed Salah**

---

## 🚀 Overview
This project is a high-fidelity, interactive web-based simulator designed to visualize line coding techniques used in digital communication systems. It serves as an instructional aid for students and engineers to understand how binary data is mapped into physical waveforms.

## 🛠 Features
* **11 Encoding Schemes:** Includes standard, differential, and multilevel signaling.
* **Real-time Visualization:** Dynamic waveform rendering as you type.
* **Educational Layout:** Explicit markers for $+V$, $0V$, and $-V$ levels with bit-boundary alignment.
* **Responsive Design:** Optimized for both desktop monitors and mobile devices for classroom use.

## 📉 Supported Encodings
1.  **Unipolar:** NRZ, RZ
2.  **Polar/Bipolar:** NRZ-L, AMI, Pseudoternary
3.  **Inversion/State-Based:** NRZ-M, NRZ-S, NRZ-I
4.  **Phase-Encoded:** Biphase-L (Manchester), Biphase-M, Biphase-S (Differential)

## 💻 Technical Implementation
The visualizer is built using a custom rendering engine on the **HTML5 Canvas API**. The core logic handles state-memory for differential schemes (tracking previous voltage levels) and pulse-shaping for return-to-zero (RZ) transitions.

## 🌐 Live Demo
Access the tool here: [https://MohammedS2lah.github.io/Interactive-Line-Coding-Visualizer/Line_Coding_Simulator.html](https://MohammedS2lah.github.io/Interactive-Line-Coding-Visualizer/Line_Coding_Simulator.html)

## 🎓 Citation
If you use this simulator in your classroom, lab, or research, please cite it as:
> Salah, M. (2026). Interactive Line Coding Visualizer. 
> Available at: https://MohammedS2lah.github.io/Interactive-Line-Coding-Visualizer/Line_Coding_Simulator.html

---
© 2026 Mohammed Salah. All rights reserved.
