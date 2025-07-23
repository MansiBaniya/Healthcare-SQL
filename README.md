# 🏥 Healthcare SQL Project

This project is a comprehensive SQL-based analysis of a healthcare system. It uses a structured relational database to simulate operations such as patient management, appointments, billing, and prescriptions.

## 📁 Dataset Structure

The dataset consists of the following main tables:

* **Patients** – Patient demographics and identifiers
* **Doctors** – Doctor details including specialty
* **Appointments** – Scheduling and appointment-related info
* **Billing** – Payment and billing records
* **Prescriptions** – Medication and dosage records

---

## 📌 SQL Objectives Covered

The project demonstrates a wide range of SQL operations, including:

### 🔎 Basic Queries

* View all records from key tables
* Retrieve appointments or prescriptions by `patient_id` or `appointment_id`

### 📊 Analytical Queries

* Appointment trends by month or year
* Patient demographics (e.g., gender distribution)
* Common appointment reasons and medication frequencies

### 💳 Billing Insights

* Total billed vs. paid amounts
* Average billing per patient
* Unpaid bills per patient
* Payment status over time

### 👩‍⚕️ Doctor Analytics

* Number of appointments per doctor
* Performance metrics and earnings by doctor
* Appointment details filtered by doctor

### 🧾 Prescriptions

* Prescriptions linked to pending payments
* Total dosage and frequency per medication

### 📆 Time-Based Reports

* Appointments within the last 30 days
* Appointments in a specific month (e.g., August)
* Daily appointment counts

### 🚫 Data Gaps

* Patients with no appointments
* Appointments with no billing records

---

## 🧪 How to Use

1. Import the SQL file:

```sql
SOURCE HealthCare\ Dataset.sql;
```

2. Make sure to run the `CREATE DATABASE` and `USE` statements at the top of the script.

3. You can execute the queries one by one to explore and analyze various aspects of the data.

---

## 📂 File

* `HealthCare Dataset.sql` – The full SQL script including table creation (if included), inserts (if any), and 40+ analysis queries.

---

## ✅ Requirements

* MySQL or any SQL-compliant RDBMS
* SQL IDE (e.g., MySQL Workbench, DBeaver, phpMyAdmin)

---

## 💡 Use Cases

* Healthcare data analysis practice
* SQL interview preparation
* Dashboard backend development for clinics/hospitals

---

## 📬 Feedback & Contributions

Feel free to fork the repo, suggest improvements, or expand the dataset with sample data!


