# RTAM – Machine Learning Module

This repository contains the **Machine Learning module** of **RTAM (Railway Track Anomaly Monitor)**, developed for the **Hack4Delhi Hackathon**.

RTAM is a multi-modal AI system designed to detect intentional railway track tampering using:
- Sensor-based vibration anomaly detection
- Camera-based visual defect detection
- Backend fusion logic for final risk assessment

---

## Repository Structure

| Folder | Description |
|------|------------|
| `sensor_ml/` | Sensor-based anomaly detection ML |
| `camera_ml/` | Camera-based visual tampering detection ML |
| `PROJECT_OVERVIEW.md` | Full RTAM system architecture & workflow |

---

## How This Repo Fits Into RTAM

This repository handles **all ML intelligence** in RTAM.

- Sensor ML → early warning via vibration anomalies
- Camera ML → visual confirmation with explainability
- Fusion logic → backend decision layer (documented here)

Frontend and backend services consume outputs from this ML module.

---

## Hackathon Context

This ML module is part of the RTAM solution proposed under the  
**Artificial Intelligence (Cross-Sector)** domain for Hack4Delhi.
