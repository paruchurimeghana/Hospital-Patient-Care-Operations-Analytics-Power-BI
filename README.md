# 🏥 Hospital Patient Care Operations Analytics

## 📌 Project Overview

Hospital Patient Care Operations Analytics is an interactive Business Intelligence project developed using **Microsoft Power BI** to analyze hospital appointments, patient behavior, treatment performance, doctor performance, and room utilization.

The project transforms raw healthcare data into meaningful **KPIs, interactive visualizations, trends, and actionable insights** to support data-driven hospital operations and decision-making.

## 🎯 Objectives

- Analyze hospital appointment demand and trends.
- Understand patient appointment behavior and preferences.
- Monitor treatment performance and operational efficiency.
- Analyze doctor workload and room utilization.
- Identify appointment and treatment-related issues.
- Provide an interactive dashboard for data-driven decision-making.

## 🛠️ Technologies Used

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Data Modeling**
- **Data Visualization**

## 📂 Dataset

The project consists of the following healthcare datasets:

- **Patients** – Patient demographic and profile information.
- **Appointments** – Appointment details, status, service type, priority, booking channel, and appointment value.
- **Treatments** – Treatment details, cost, duration, and treatment status.
- **Doctors** – Doctor information and specialization.
- **Rooms** – Hospital room information and utilization details.
- **Date Table** – Date dimension used for time-based analysis.

## 🔄 Data Preparation

Data preparation was performed using **Power Query**, including:

- Data profiling and quality validation
- Handling missing and blank values
- Removing duplicate records
- Trimming unnecessary spaces
- Standardizing categorical values
- Correcting data types
- Data cleaning and transformation
- Creating relationships between tables
- Preparing data for analysis and visualization

## 🧩 Data Model

The project uses a structured relational data model with the following relationships:

Patients (1) ────────< Appointments

Doctors (1) ────────< Appointments

Appointments (1) ───< Treatments

Doctors (1) ────────< Treatments

Rooms (1) ──────────< Treatments

Date Table (1) ─────< Appointments

# 📊 Dashboard Pages

# 1. Appointment Demand
Analyzes overall appointment demand and booking patterns.

# Key KPIs:
Total Appointments
Total Appointment Value
No-Show Rate
Cancellation Rate

# Visualizations:
Appointment Demand Trend
Appointments by City
Appointments by Service Type
Appointment Booking Channels

# 2. Patient Appointment Behaviour
Analyzes patient activity and appointment preferences.

# Key KPIs:
Total Patients
Average Appointments per Patient
Total Appointment Value
Active Patients

# Visualizations:
Patients by City
Patient Type Distribution
Patient Appointment Frequency
Appointment Preference by Time Slot

# 3. Treatment Performance
Analyzes treatment activity and operational performance.

# Focus Areas:
Treatment Volume
Treatment Cost
Treatment Status
Treatment Trends
Treatment Performance
4. Doctor & Room Performance

Analyzes healthcare resource utilization and operational workload.

# Focus Areas:
Doctor Appointment Volume
Doctor Treatment Activity
Doctor Workload
Room Utilization
Resource Performance

# 5. Appointment & Treatment Problems
Identifies operational issues affecting patient services.

# Focus Areas:
No-Shows
Cancellations
Appointment Issues
Treatment Delays
Operational Problem Areas

# 6. Executive Summary
Provides a consolidated overview of hospital operational performance.

# Includes:
Overall KPIs
Appointment Trends
Patient Activity
Treatment Performance
Operational Insights
Key Business Observations

# 💡 Key Insights
The dashboard enables analysis of:

Appointment demand across different time periods.
Appointment volume across cities and service types.
Patient appointment frequency and preferences.
No-show and cancellation patterns.
Treatment performance and utilization.
Doctor workload and room utilization.
Operational issues affecting patient care services.

# 🚀 Business Value
This project demonstrates the use of Power BI, Power Query, DAX, and data modeling to convert raw healthcare data into an interactive Business Intelligence solution.
The dashboard supports operational monitoring, performance analysis, trend identification, and data-driven decision-making for hospital patient care operations.

# 👩‍💻 Skills Demonstrated
# Power BI | Power Query | DAX | Data Cleaning | Data Transformation | Data Modeling | Data Visualization | KPI Development | Business Intelligence | Healthcare Analytics

# 👩‍💻 Author
# Paruchuri Meghana
