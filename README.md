=========================================
      TRAFFIC LIGHT SIMULATOR - README
=========================================

📄 ABOUT
--------
This is a command-line simulation of a 4-way intersection traffic light system with the following features:

✔️ Dynamic car spawning on multiple lanes
✔️ Intelligent traffic light phase control with prioritization
✔️ Left-turn prioritization based on car counts
✔️ Miller Parkway priority rules
✔️ Fully simulated train crossing that blocks Miller Parkway traffic
✔️ Yellow light transitions and minimum/maximum green durations

This simulation is written in C# and designed to run as a standalone .exe file.
No installation is required.

👨‍🏫 PROJECT PURPOSE
---------------------
This simulation was developed as part of a final project to demonstrate traffic logic programming, condition-based event scheduling, and rule enforcement in a C# console environment.

⚙️ HOW TO RUN
-------------
1. **Download the executable file** from the link provided in the project PDF.
2. **Double-click** the `.exe` file. No installation or setup is required.
3. The simulation starts automatically in a command-line window.

📦 FILES
--------
- `TrafficSimulator.exe`       ← Main executable
- `README.txt`                 ← This file

⌨️ CONTROLS
-----------
- Press `T` on your keyboard at any time to **trigger a train** crossing.
  - The train blocks Miller Parkway traffic for 10 seconds.
  - A message will show when the train is active and when it clears.
- Traffic logic will display in real time — including:
  - Car spawns
  - Light transitions (Green → Yellow → Red)
  - Priority activations for left turns and Miller Parkway
  - Current light state every few seconds

📋 NOTES
--------
- This application is intended for demonstration and academic purposes.
- If the console closes immediately, try running it from a Command Prompt window to keep the output open.

🔗 Project link: [(https://drive.google.com/drive/folders/1CZEXB1EgvdjBDlp-LVYe7ywc6FqHHzQF?usp=sharing)] 

Thank you for reviewing this project!

— Ethan Tyner
