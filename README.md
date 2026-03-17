# Hospital-management-system-HMS-
A Hospital Management System (HMS) streamlines hospital operations—patient admissions, doctor scheduling, billing, and records—replacing manual processes for efficiency. It's a popular student/professional project using databases and web technologies.


📋 Project Overview
A comprehensive Hospital Management System built with Streamlit and SQLite, designed to streamline healthcare operations including patient management, doctor scheduling, appointment tracking, bed allocation, and financial reporting.

✨ Features
👥 Patient Management
Register new patients with detailed information

Track patient admissions, discharges, and transfers

Maintain medical history and records

Search and filter patients by various criteria

Emergency contact management

👨‍⚕️ Doctor Management
Complete doctor profiles with specializations

Real-time availability tracking

Schedule management

Performance analytics and ratings

Patient load monitoring

📅 Appointment System
Schedule and manage appointments

Calendar view for easy tracking

Automated reminders

Multiple appointment types

Payment tracking

🛏️ Bed Management
Real-time bed occupancy tracking

Bed allocation and release

Floor-wise bed mapping

Cleaning schedule management

Different bed types (ICU, General, Private, etc.)

📊 Reports & Analytics

Patient statistics and demographics

Financial reports and revenue tracking

Doctor performance metrics

Department-wise analysis

Appointment analytics

⚙️ System Administration

User authentication and roles

Hospital information management

Backup and restore functionality

Data export capabilities

Activity logging

🛠️ Technology Stack
Frontend: Streamlit

Backend: Python

Database: SQLite

Data Visualization: Plotly

Data Processing: Pandas

Authentication: Hashlib

📁 Project Structure
text
HMS/
│
├── hospital_management_system.py   # Main Streamlit application
├── database.py                      # Database operations and models
├── api.py                           # API wrapper for database
├── run.py                           # Application runner
├── setup.py                          # Setup script
├── db_viewer.py                      # Database viewer utility
├── requirements.txt                  # Python dependencies
├── hospital.db                        # SQLite database (auto-generated)
└── README.md                          # Project documentation
🚀 Installation Guide

Prerequisites
Python 3.8 or higher

pip package manager

Step 1: Clone the Repository
bash
git clone https://github.com/yourusername/HMS.git
cd HMS
Step 2: Create Virtual Environment (Optional but Recommended)
bash

# Windows
python -m venv venv
venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
Step 3: Install Dependencies

bash
pip install -r requirements.txt
Step 4: Initialize Database
bash
python setup.py
Step 5: Run the Application
bash
python run.py
