MARGA-DARSHAK
AN AI-POWERED ROUTE SAFETY FOR NORTH EASTERN FRIEGHT.

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

## Quick Start
```bash
git clone [https://github.com/your-username/marga-darshak.git](https://github.com/your-username/marga-darshak.git)
cd marga-darshak
npm install
# Set GEMINI_API_KEY in your .env file
npm run dev
