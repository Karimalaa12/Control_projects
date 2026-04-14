# Control_projects

🚀 Motor Drive Control System (Forward/Reverse with Frequency Steps)
📌 Overview

This project implements a motor drive control system using a Variable Frequency Drive (VFD) controlled by a PLC.

The system controls motor speed and direction (Forward/Reverse) using predefined frequency steps and timing sequences, simulating real industrial automation processes.

🧰 Hardware & Tools Used
PLC: Siemens S7-1200
Motor Drive (VFD): Siemens G120 (SINAMICS)
AC Induction Motor
Control wiring & digital inputs

⚙️ System Operation
🔁 Forward Direction:
Start at 15 Hz
After 5 seconds → increase to 30 Hz
After 5 seconds → increase to 50 Hz
Continue running at 50 Hz for 30 seconds

🔄 Reverse Direction:
Switch to Reverse
Run at 50 Hz
After 5 seconds → decrease to 30 Hz
After 5 seconds → decrease to 15 Hz

🔁 Cycle Repeat:
Return to Forward direction
Restart from 15 Hz
Repeat the full sequence automatically

🎯 Objectives
Control motor speed using frequency (Hz) via VFD
Implement smooth Acceleration & Deceleration
Control Forward and Reverse rotation
Apply PLC-based automation logic

🧠 Key Concepts
PLC Programming (Ladder Logic / TIA Portal)
VFD Speed Control
Industrial Automation Sequences
Timing & State Control
Motor Protection & Smooth Operation

🛠️ Implementation Details
Frequency levels: 15 Hz, 30 Hz, 50 Hz
Time intervals:
5 seconds (transition steps)
30 seconds (steady operation)
PLC handles:
Timing logic
Direction switching
Command signals to VFD
