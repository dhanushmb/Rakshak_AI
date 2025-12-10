# 🚨 Rakshak AI --- AI-Powered Comprehensive Security Solution

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue) ![Made
With](https://img.shields.io/badge/Made%20with-❤️%20AI%20&%20Flutter-red)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange)

Rakshak AI is an end-to-end **AI-driven surveillance & security
ecosystem** designed to empower **law enforcement, on-duty personnel,
and citizens** with real-time intelligence, incident reporting, and CCTV
analytics.

It integrates **Machine Learning, Deep Learning, and LLMs** to automate
incident detection, streamline communication, and enhance emergency
response capabilities.

## ✨ Table of Contents

-   Overview
-   Problem Statement
-   Features
-   Architecture
-   Tech Stack
-   Installation
-   Project Structure
-   Screenshots
-   Contributors
-   License

# 📌 Overview

Rakshak AI provides: - Web Dashboard for administrators
- Mobile App for on-duty police personnel
- Citizen App for alerts and CCTV access

The system uses CCTV streams + AI models to detect: - Accidents
- Crimes
- Suspicious activities
- Anomalies

It delivers instant notifications, enriched insights, and a complete
security workflow.

# 🚨 Problem Statement

-   Security personnel cannot manually monitor hundreds of CCTV feeds
    effectively.
-   Human fatigue and errors lead to delayed responses and missed
    incidents.
-   On-ground officers lack real-time synchronization with monitoring
    centers.
-   Citizens do not have a verified way to receive or report incidents.

Rakshak AI solves all the above with automated monitoring +
communication + AI analytics.

# 🚀 Features

## 🖥️ Web Dashboard (Admin Panel)

-   Interactive analytics dashboard displaying all incidents
-   Geo-mapped CCTV viewer with live stream access
-   Real-time incident detection using AI models
-   Automated alerts & notifications
-   LLM-powered natural language insights
-   Feedback learning for false positives/negatives
-   Monitor on-duty personnel statuses

## 👮🏻‍♂️ Mobile App (On-Duty Personnel)

-   Report incidents with type, description & media
-   Track status of submitted incident reports
-   Multi-language UI

## 👥 Citizen Mobile App

-   Alerts for nearby incidents
-   Map view of verified incidents
-   Access to public CCTV streams

# 🏗️ Architecture

CCTV Streams → AI Detection Server → FastAPI Backend → MongoDB & S3\
        ↓\
      Web Admin Dashboard\
        ↓\
  On-Duty App ↔ Citizens App (Flutter)

# 🛠️ Tech Stack

**Frontend**: React, TypeScript, Mapbox, Google Maps SDK
**Mobile**: Flutter, Dart, BLoC
**Backend**: FastAPI, MongoDB, AWS S3, Uvicorn
**AI Models**: YOLO, TensorFlow, PyTorch, Mixtral-8x7B

# ⚙️ Installation & Setup

## Mobile App (Flutter)

    cd App
    flutter pub get
    flutter run

## Frontend

    cd Frontend
    npm install
    npm run dev

## Backend (FastAPI)

    cd Backend
    python -m venv venv
    source venv/bin/activate      # Windows: venv\Scripts\activate
    pip install -r requirements.txt
    uvicorn main:app --reload --port=5000

## Video Streaming Server

    cd video-server
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    python video_server.py

# 📂 Project Structure

Rakshak-AI\
├── Frontend\
├── App\
├── Backend\
├── video-server\
├── models\
├── scripts\
└── README.md

# 📜 License

MIT License
