# HostelOS
The Future of Hostel Management

![React](https://img.shields.io/badge/react-18.x-blue)
![FastAPI](https://img.shields.io/badge/fastapi-backend-green)
![Three.js](https://img.shields.io/badge/three.js-3D-black)
![Tailwind](https://img.shields.io/badge/tailwindcss-ui-38B2AC)
![SQLite](https://img.shields.io/badge/sqlite-db-07405E)

![API](https://img.shields.io/badge/api-rest-lightgrey)
![Auth](https://img.shields.io/badge/auth-rbac-blueviolet)
![Status](https://img.shields.io/badge/status-active-success)

## Overview
HostelOS is a full stack system designed to digitize hostel operations through structured backend services and a unified interface It replaces manual workflows with scalable modules for tracking access control and internal coordination

The platform integrates visualization data systems and role based permissions into a single environment enabling efficient and maintainable hostel management

## System Design

Client Layer  
React based frontend handling UI rendering and state management  

API Layer  
FastAPI service exposing modular endpoints  

Data Layer  
SQLite with structured schema and migration scripts  

Control Layer  
Role based access control for admin and student operations  

Visualization Layer  
3D representation using React Three Fiber  

## Core Modules

Digital Twin  
Real time room visualization mapped to backend state  

Marketplace  
Controlled student trading system  

Mess System  
Identity linked access with usage tracking  

Attendance  
Geolocation based validation system  

Mailroom  
Parcel tracking with secure verification  

Energy Monitoring  
Room level usage tracking and aggregation  

Gate Pass  
QR based entry system with logs  

## Getting Started

Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

python migrate_db.py
python migrate_parcels.py
python migrate_marketplace.py

uvicorn main:app --reload
```

Frontend
```bash
cd frontend
npm install
npm run dev
```

## Access

Admin  
username admin  
password admin  

Student  
username 9328994892  
password 9328994892  

## Notes
Built as a hackathon project and extended into a system design focused backend platform
