# Fire Hazard Mapping and Incident Reporting System

A Web GIS platform designed for spatial risk assessment, hazard mapping, and time-series incident forecasting within Mandaluyong City, developed as a Capstone Research Project at José Rizal University.

---

## Overview

Assessing urban fire vulnerabilities requires spatial data analysis combined with historical incident patterns. This platform was developed to map high-risk zones, track municipal fire incidents, and support spatial decision-making by integrating BFP Mandaluyong datasets into an interactive mapping interface.

---

## Tech Stack & Data Tools

- Frontend: React.js
- Mapping & Geolocation: Google Maps API, GeoJSON (Barangay boundaries, fire hydrant locations, incident hotspots)
- Backend & Data Processing: Python, Pandas (API construction, dataset transformation, and data cleaning)
- Data Analysis & Preprocessing: Microsoft Excel (Data filtering, tabulation, and initial analysis)

---

## Key Features

- Interactive Web GIS Mapping: Renders custom GeoJSON layers to distinguish barangay boundaries, fire hydrant networks, and historical incident hotspots.
- BFP Dataset Integration: Processes raw operational data from the Bureau of Fire Protection (BFP) Mandaluyong, including incident records and infrastructure locations.
- Data Processing Pipeline: Uses Python and Pandas to clean, filter, and format multi-source municipal datasets into structured API endpoints for frontend rendering.
- Spatial Risk Assessment: Overlays infrastructure inventory against incident frequency to highlight safety gaps and high-risk urban zones.

---

## System Workflow

1. Data Preprocessing: BFP datasets on fire incidents, hydrant inventory, and municipal statistics are organized and cleaned using Excel and Pandas.
2. Spatial Mapping & Boundary Setup: GeoJSON files are configured to segment Mandaluyong City barangay boundaries and map infrastructure coordinates.
3. Backend Service: Python-based services process spatial data and deliver structured API payloads to the web interface.
4. Interface Rendering: The React.js frontend interacts with Google Maps API to display interactive overlays and spatial analytics.

---

*Developed as a Capstone Research Project at José Rizal University in collaboration with BFP Mandaluyong.*
