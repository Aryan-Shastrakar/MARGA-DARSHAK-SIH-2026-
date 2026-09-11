MARGA-DARSHAK ( AN AI-POWERED ROUTE SAFETY FOR NORTH EASTERN FRIEGHT. )

## Key Features
* **GIS & Radar Tracking**: Live freight GPS, Open-Meteo weather telemetry, and RainViewer Doppler radar on an interactive Leaflet map.
* **AI Route Optimization**: Gemini 3.7 Flash computes safe dry bypass routes (e.g., Umkiang pass) based on live hazards and cargo urgency.
* **Incident Reporting**: Crowd-sourced landslide and pass-blockage reporting with direct photo uploads and clearance tracking.
* **Vehicle & Driver Telematics**: Real-time monitoring of truck ECU metrics (RPM, coolant, cargo status) and driver vitals.

## Tech Stack
* **Frontend**: React, Tailwind CSS, Leaflet.js
* **Backend**: Node.js, Express.js
* **AI Engine**: Google Gemini 3.7 Flash API
* **Data Feeds**: Open-Meteo API, RainViewer Radar API
* **Database**: SQLite / PostgreSQL

DASHBOARD
https://github.com/Aryan-Shastrakar/MARGA-DARSHAK-SIH-2062-/blob/f85d1df83657eb1a8b3a48accaa974ac85b57fd9/WhatsApp%20Image%202026-09-02%20at%209.32.25%20PM.jpeg

ALERTS
https://github.com/Aryan-Shastrakar/MARGA-DARSHAK-SIH-2062-/blob/f85d1df83657eb1a8b3a48accaa974ac85b57fd9/WhatsApp%20Image%202026-09-02%20at%209.32.23%20PM.jpeg

LIVE MAP
https://github.com/Aryan-Shastrakar/MARGA-DARSHAK-SIH-2062-/blob/f85d1df83657eb1a8b3a48accaa974ac85b57fd9/WhatsApp%20Image%202026-09-02%20at%209.32.24%20PM%20(2).jpeg

## Quick Start
```bash
git clone [https://github.com/your-username/marga-darshak.git](https://github.com/your-username/marga-darshak.git)
cd marga-darshak
npm install
# Set GEMINI_API_KEY in your .env file
npm run dev
