# Patient Management System (C++ Console Application)

## Description

A console-based C++ application designed to streamline hospital operations such as patient record management, appointment scheduling, billing, and insurance validation. The system reduces manual effort, minimizes errors, and improves accessibility of healthcare data for administrative and clinical use.

## Problem Statement

Healthcare facilities often manage large volumes of patient data, appointments, and billing records manually, leading to inefficiencies, errors, and data inconsistency. This project provides a structured, digital solution using object-oriented programming concepts to improve reliability and scalability.

## Objectives

* Efficient storage and retrieval of patient records
* Appointment scheduling with doctor availability checks
* Billing generation and insurance eligibility validation
* Practical implementation of object-oriented programming concepts in C++

## Core Functionalities

* Inpatient and outpatient patient registration
* Patient detail management (personal and medical data)
* Doctor specialization selection and slot allocation
* File-based doctor and availability management
* Billing calculation with insurance validation

## Object-Oriented Concepts Used

### Inheritance

* Patient (base class) extended by Inpatient and Outpatient classes
* Billing (base class) extended by Insurance class

### Polymorphism

* Runtime polymorphism implemented using function overriding
* Dynamic display of patient details based on patient type

### File Handling

Doctor and slot details are stored in department-specific files and loaded dynamically during appointment scheduling.

Departments include Cardiology, Neurology, Nephrology, Oncology, Radiology, and General Medicine.

### Exception Handling

User-defined exceptions are implemented to validate inputs such as phone number, blood pressure, weight, and date formats using try-catch blocks.

### Templates

Function templates are used to improve code reusability and support generic input validation.

## Technologies Used

* C++ (Object-Oriented Programming)
* File Handling (ifstream, ofstream)
* Exception Handling
* Function Templates

## Program Flow

1. Select inpatient or outpatient mode
2. Enter patient details
3. Choose doctor specialization
4. Load doctor and slot availability from file
5. Confirm appointment
6. Generate billing and validate insurance

## How to Run

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Compile the program:

   ```bash
   g++ main.cpp -o patient_management
   ```
3. Run the executable:

   ```bash
   ./patient_management
   ```
4. Ensure all department files are present in the same directory as the executable.

