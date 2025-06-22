System Resource Monitor

# Description
A Python desktop tool that shows **real-time CPU, RAM, Disk, and Network usage** using `psutil` and `matplotlib`. It provides visual insights into system performance through live plots, making it useful for debugging, learning, or general monitoring.

# Features
- Real-time CPU, memory, disk, and network monitoring
- Live graphical display using `matplotlib`
- Auto-refreshes system usage stats
- Lightweight and easy to use

# Technologies
- Python 3.x
- psutil
- matplotlib

# Getting Started

# Create and activate a virtual environment
```bash
python -m venv .venv

#Windows
.\.venv\Scripts\activate

#macOS/Linux
source .venv/bin/activate
Install dependencies
pip install -r requirements.txt

Run the app
python system_monitor.py
Requirements
psutil
matplotlib
