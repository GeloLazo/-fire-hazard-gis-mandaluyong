# Fire Hazard Mapping and Incident Reporting System

A full-stack Web GIS platform designed for spatial risk assessment, hazard mapping, and time-series incident forecasting within Mandaluyong City.

---

## Overview

Assessing urban fire vulnerabilities requires spatial data analysis combined with historical incident patterns. This platform was developed to map high-risk zones, track municipal fire incidents, and support spatial decision-making through interactive web mapping and predictive data modeling.

---

## Tech Stack

- Frontend: React, TypeScript, HTML, CSS
- Backend: Node.js, Express
- Database: PostgreSQL (with spatial data extensions)
- GIS & Mapping: Leaflet / OpenLayers integration
- Forecasting: Time-series statistical models

---

## Key Features

- Interactive Web GIS Mapping: Visualizes fire incident hotspots, barangay boundaries, and high-risk zones using custom map layers.
- Incident Reporting Dashboard: Allows authorized users to log, update, and monitor local fire safety incidents in real time.
- Time-Series Forecasting: Integrates analytical models to project future incident trends based on historical municipal data.
- Role-Based Access: Secures administrative controls for managing hazard data and user records.

---

## System Architecture

1. Data Collection & Storage: Incident logs and spatial coordinates are stored and managed in a PostgreSQL database.
2. Backend Services: Node.js and Express REST APIs handle data queries, user authentication, and forecasting requests.
3. Spatial Rendering: The React frontend renders interactive maps and dashboard metrics for end-users and administrators.

---

*Developed as a capstone research and software development project for Mandaluyong City.*
