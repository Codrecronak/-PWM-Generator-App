# 🔧 PWM Signal Generator App

This is a MATLAB-based GUI app that generates and visualizes **Pulse Width Modulation (PWM)** signals using user-defined carrier and modulating signals.

## 🎯 Aim

To provide an interactive platform where users can:
- Input a carrier wave (triangular or sawtooth)
- Input a modulating wave (typically sinusoidal)
- View the resulting PWM signal in real-time

## 📚 Background

**Pulse Width Modulation (PWM)** is a technique used to encode analog signals into a digital format by varying the duty cycle of a square wave. It is widely used in:
- Motor control
- Power electronics
- Signal modulation

### Key Components:
- **Carrier Wave**: High-frequency triangular or sawtooth waveform
- **Modulating Signal**: Low-frequency sinusoidal or arbitrary signal
- **Comparison Logic**: PWM output goes high (`1`) when modulating > carrier, else low (`0`)

## 🧠 How It Works

1. **Input**:
   - Users provide the frequency and amplitude for both the carrier and modulating waves through the GUI.

2. **Process**:
   - The app compares the two signals to generate a PWM signal.

3. **Output**:
   - The resulting PWM waveform is plotted in real-time within the app.
   - The duty cycle dynamically changes with the modulating signal.

## 🖼️ UI Preview

*Screenshots and signal graphs from the app can be added here.*

## ✅ Features

- MATLAB GUI-based signal input
- Real-time PWM visualization
- Adjustable signal parameters (frequency, amplitude)
- Educational tool to learn PWM concepts

## 🚀 Future Scope

This app can be extended for practical engineering applications such as:
- Motor speed control
- LED brightness modulation
- Digital-to-analog conversion techniques

## 📁 Project Status

✅ Completed basic GUI app with signal visualization  
🔜 Future versions may include waveform export, hardware interfacing, and advanced signal types.

---

Made with MATLAB 💻
