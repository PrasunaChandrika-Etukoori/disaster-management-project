#  SmartMatch: AI-Powered Disaster Management System

A full-stack disaster management system that uses **Natural Language Processing (NLP)** and **Geospatial Analysis** to detect disaster locations from text and match them with nearby relief resources.

---

## Project Overview

SmartMatch is designed to improve disaster response by:

* Extracting **location and resource needs** from unstructured text (tweets, reports)
* Identifying **affected areas**
* Matching them with **nearest relief hubs**
* Visualizing results on an interactive dashboard

This system reduces manual effort and improves response efficiency during disasters.

---

##  Tech Stack

### Frontend

* React.js
* Vite
* Tailwind / CSS

### Backend

* Python (Flask)
* spaCy (NER Model)
* NLP Processing

### Other Tools

* Geocoding APIs
* Leaflet (Map Visualization)

---

## Key Features

* **Disaster Detection from Text**

  * Input: "Severe flooding in New Zealand"
  * Output: Location + Disaster Type

* **Location Extraction (NER Model)**

  * Uses NLP to detect places from text

* **Interactive Map**

  * Shows affected location and nearby relief hubs

*  **Relief Matching System**

  * Matches needs with closest resources

* **Donation & Help Request System**

  * Users can donate or request help

* **Donor Dashboard**

  * Tracks donations and impact

---

## 📸 Screenshots

### 🔹 Main Interface

* Disaster input and detection system

### 🔹 Detection Output

* Shows location, disaster type, severity, and nearby hubs

### 🔹 Map Visualization

* Displays affected areas with radius

### 🔹 Donation & Request Pages

* User interaction system for aid

### 🔹 Dashboard

* Tracks donations and pending requests

---

## How to Run Locally

### 🔹 Backend

```bash
cd backend
pip install -r requirements.txt
python app.py
```

### 🔹 Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## Model Details

* **BERT-based classifier** for disaster detection
* **spaCy NER model** for extracting:

  * Location (LOC)
  * Organization (ORG)
  * Needs (NEED)

Model Performance:

* Accuracy: ~94%
* F1 Score: ~93%

---

## How It Works

1. User enters disaster-related text
2. NLP model processes input
3. Location is extracted
4. Coordinates are generated
5. Nearby relief hubs are identified
6. Results are displayed on dashboard

---

## Research Base

This project is based on the research:

*SmartMatch: An AI-powered Disaster Relief Resource Matching System using NLP and Geospatial Optimization* 

---

## Future Improvements

* Multilingual support
* Real-time Twitter API integration
* Cloud deployment
* Advanced analytics dashboard

---

## Acknowledgment

Developed as part of academic research at VIT Chennai.

---

## Show your support

If you found this project useful:

* ⭐ Star this repo
* 🍴 Fork it
* 📢 Share it

---
