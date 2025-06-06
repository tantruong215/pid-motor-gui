# DC Motor PID Control with Live Tuning GUI

Built a closed-loop speed control system for a brushed DC motor using PID control on Arduino and a Python-based GUI for real-time tuning.

## Hardware Setup
- Maxon 225089 DC Motor (100 W)
- 1024 PPR quadrature encoder
- Arduino Mega 2560
- 12 V power supply

## Control System
- PID algorithm implemented on Arduino
- GUI built in Python with Tkinter
- Live tuning of Kp, Ki, Kd
- Real-time plotting at 100 Hz

## Results
- ±1 RPM steady-state error at 1000 RPM
- Settling time < 0.2 s with overshoot < 5%
- 10,000+ data points logged during tuning

## Tools Used
- Arduino IDE
- Python (Tkinter, Matplotlib)
- Excel/CSV log analysis

## Project Status
In Progress – Summer 2025
