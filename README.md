# MediSched AI

An intelligent healthcare scheduling system that manages patient records, doctor availability, and slot-based appointment booking.

Features:
- Patient management (by staff)
- Doctor slot scheduling (30 min / 1 hour)
- Smart appointment booking system

# Problem Statement

In many hospitals and clinics, appointment scheduling is still done manually or using basic systems. This leads to:

Long waiting times
Double bookings or missed appointments
Inefficient use of doctor time
Poor patient experience

# Objective
Automate appointment booking
Reduce scheduling conflicts
Improve doctor time utilization
Enhance patient experience



# Key Features
🧑 Patient Management
Add and update patient records (by staff)
Store medical history and contact details

# 👨‍⚕️ Doctor Scheduling
Define available working hours
Set consultation duration (30 mins / 1 hour)

# 📅 Smart Appointment Booking
Prevents double bookings
Suggests optimal available slots


# 🗄️ Database Design

# 🧑 Patients Table
Stores patient details entered by staff
patient_id
name
age
contact
medical_history

# 👨‍⚕️ Doctors Table
Stores doctor availability and slot settings
doctor_id
name
available_from
available_to
slot_duration (30 mins / 1 hour)

# 📅 Appointments Table
Stores booking details
appointment_id
patient_id
doctor_id
time_slot


# ⚙️ How It Works
Staff adds patient details
Doctor sets availability and slot duration
System generates time slots automatically
Patient selects preferred slot
System checks availability and confirms booking


# 📊 Success Metrics
Leading Indicators
Number of appointments booked
Reduced manual work
Increased slot utilization
Lagging Indicators
Reduced waiting time
No double bookings
Improved patient satisfaction


# ⚠️ Current Challenges (As-Is)
Manual patient record management
Informal doctor availability tracking
Manual appointment scheduling
No structured slot system
High chances of overlap and inefficiency


# 💥 Pain Points
Fragmented patient data
Inefficient scheduling process
Double bookings
Poor patient experience
Lack of real-time updates


# 🚧 Constraints
Limited time (hackathon/project deadline)
Budget constraints (use of open-source tools)
Data privacy requirements
Limited tech stack
No external system integration


# 🛠 Tech Stack
Frontend: React.js
Backend: Flask / Spring Boot
Database: MySQL
AI Logic: Python

# 👥 Stakeholders
Hospital Staff
Doctors
Patients
Developers

