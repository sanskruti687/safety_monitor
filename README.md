# safety_monitor
This is an AI-powered system that analyzes live camera feeds to monitor worker safety in real-time. It automatically detects safety violations, such as missing PPE, and sends instant alerts to a web dashboard

🛡️ AI Worker Safety Monitoring System
This project is an AI-powered system that analyzes live camera feeds to monitor worker safety in real-time. It automatically detects simulated safety violations, such as missing PPE, and sends instant alerts to a web dashboard.

This is a representative image. A screenshot of the actual application should be placed here

✨ Features
Real-time Camera Feed: Accesses the user's webcam for live video monitoring

Simulated AI Detection: The backend simulates the detection of safety violations (e.g., missing helmets or vests).

WebSocket Alerts: Pushes real-time alerts and detection data to the frontend for instant updates.

Interactive Dashboard: Displays a live video feed, a running list of recent alerts, and key safety statistics.

Dynamic Controls: Allows users to select a camera source, start/stop monitoring, and capture still images of violations.

🛠️ Tech Stack
Frontend: HTML5, CSS3, Vanilla JavaScript (ES6+)

Backend: Python with Flask

Real-time Communication: gevent-websocket for handling WebSockets with Flask.

Database: SQLite 3 for lightweight, file-based data storage.

📁 Folder Structure
The project is organized with a simple and clean structure.

safety_monitor/
├── captures/           # Stores images captured from the dashboard
├── index.html          # The single-page frontend application
├── app.py              # The Flask backend server with all API and WebSocket logic
├── database_setup.py   # A one-time script to initialize the database
├── README.md           # This readme file
└── safety_monitor.db   # The SQLite database file (created by the setup script)

# Demo Application 
<img width="949" height="440" alt="image" src="https://github.com/user-attachments/assets/2029ace1-4624-49d5-849f-1dff2c51d9ff" />

<img width="923" height="436" alt="image" src="https://github.com/user-attachments/assets/22600d67-267f-4740-92b2-8ed0ec3f89a6" />

