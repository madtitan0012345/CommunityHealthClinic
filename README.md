# Community Health Clinic Management System

**Unit:** BN231 - Software Development Skills and Tools  
**Assessment:** Assignment 2 - Group Assignment  
**Architecture:** Model-View-Controller (MVC)  
**Language:** Java (Swing GUI)  
**IDE:** Apache NetBeans

## Project Overview
A desktop application for a community health clinic to manage patient registrations, doctor allocations, appointment scheduling, and treatment records. The system replaces manual record-keeping with a robust, file-backed Java application.

## Features
- **Patient Management:** Register, update, search, and delete patients.
- **Doctor Management:** Register doctors with specialisations and availability.
- **Appointment Booking:** Schedule appointments with double-booking prevention.
- **Treatment Entry:** Record diagnoses and prescriptions, auto-completing appointments.
- **Searching & Sorting:** Custom implementation of Linear/Binary search and Bubble/Insertion/Quick sort.
- **Data Persistence:** Save and load all records via flat-file I/O (`data/*.txt`).
- **Reports:** Generate appointment summaries and doctor schedules.

## Architecture (MVC)
- **Model:** `model` package (Patient, Doctor, Appointment, Treatment, Clinic).
- **View:** `view` package (Swing panels, MainMenuFrame).
- **Controller:** `controller` package (PatientController, DoctorController, etc.).

## How to Run
1. Open the project in Apache NetBeans.
2. Ensure JUnit 4 is added to the Test Libraries.
3. Press **F6** to run the application.
4. Press **Alt+F6** to execute the JUnit test suite.

## Test Coverage
All 5 test classes pass successfully (`Tests run: 30, Failures: 0, Errors: 0`).
