Netdata Monitoring Task

This project sets up Netdata for real-time system monitoring on Linux using MobaXterm for terminal access. Netdata provides live CPU, memory, disk, network, and process statistics via a web dashboard.

🚀 Setup
# Install Netdata
bash <(curl -Ss https://my-netdata.io/kickstart.sh)

# Start & Enable Service
sudo systemctl start netdata
sudo systemctl enable netdata


Access Dashboard → Local: http://localhost:19999 
(Optional) Connect to Netdata Cloud for centralized monitoring.

📊 Features

Real-time metrics with graphs

Alerts & notifications

Lightweight and fast

🛠 Tools

Linux (Ubuntu) • MobaXterm • Netdata • GitHub

📂 Structure
netdata-monitoring-task/
│── screenshots/   # Dashboard captures
│── README.md

Screenshots:-
<img width="1897" height="967" alt="image" src="https://github.com/user-attachments/assets/06fc28ce-7c78-4826-af80-7df031c38957" />
<img width="1815" height="947" alt="netdata" src="https://github.com/user-attachments/assets/fb448569-876e-42a2-84c8-abab9edfe78e" />

Author: Abhilash Shivarchaka
