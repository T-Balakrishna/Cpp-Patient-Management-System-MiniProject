# 🏥 Patient Management System — C++ (Console Application)

A **console-based C++ application** designed to simplify and automate hospital operations such as patient data management, appointment scheduling, billing, and insurance validation.  
This project aims to minimize manual errors, reduce paperwork, and enhance access to crucial healthcare information for both administrative and clinical staff.

---

## 🩺 Problem Statement

Healthcare facilities often struggle to handle large volumes of information such as patient details, medical history, appointments, and billing records.  
Manual handling can lead to **errors, inefficiencies, and data loss**.  

This **Patient Management System** provides a digital and efficient solution, improving accuracy, scalability, and accessibility while reducing the need for excessive manpower.

---

## 🎯 Objectives

- 🧾 Store, track, and access **patient records** efficiently.  
- 🩹 Enable **appointment scheduling** and check **doctor availability**.  
- 💳 Keep track of all **payment and billing details**.  
- 🧮 Validate **insurance eligibility** during patient checkout.  
- ⚙️ Implement **object-oriented concepts** such as inheritance, polymorphism, file handling, templates, and exception handling.

---

## 🧱 Core Functionalities

1. Choose between **Outpatient** or **Inpatient** entry modes.  
2. Enter and manage **patient details** (name, age, contact, BP, weight, etc.).  
3. **Select doctor specialization** such as Cardiology, Neurology, Oncology, etc.  
4. **Doctor names and slot availability** are fetched directly from files for each department.  
5. **Schedule appointments** automatically based on department and availability.  
6. Generate and process **billing and insurance validation**.

---

## 🧮 Object-Oriented Concepts Used

### 🧬 Inheritance

- **Hierarchical Inheritance:**  
  - `Patient` (Base Class) → `Inpatient`, `Outpatient` (Derived Classes)  
  - Used to inherit and manage shared patient details like name, BP, weight, and contact information.
  
- **Single Inheritance:**  
  - `Billing` (Base Class) → `Insurance` (Derived Class)  
  - Used to calculate billing details, apply insurance validation, and deduct eligible amounts.

---

### 🔁 Polymorphism

- **Runtime Polymorphism** implemented using **function overriding**.  
- The `display()` function is defined in:
  - `Patient` → Displays general patient info.  
  - `Inpatient` → Displays details specific to admitted patients.  
  - `Outpatient` → Displays outpatient details.  

This enables dynamic handling of different patient objects at runtime.

---

### 📂 File Handling

Doctor information is stored and retrieved from six department-specific files, each containing:
- Doctor Name  
- Available Slots  

**Departments Included:**
- 🫀 Cardiology  
- 🧠 Neurology  
- 🧬 Nephrology  
- 🎗️ Oncology  
- 🦴 Radiology  
- 💊 General Medicine  

These files are read dynamically when a department is selected to schedule appointments.

---

### ⚠️ Exception Handling

Implemented custom **user-defined exceptions** to validate critical inputs and prevent runtime errors.  

Exceptions handled include:
- Invalid **Phone Number** format  
- Unreasonable **Weight** or **Blood Pressure** input  
- Incorrect **Date format** or invalid date value  

C++ `try`, `catch`, and `throw` blocks are used to control and handle erroneous inputs gracefully.

---

### 🧩 Templates

Utilizes **function templates** for code reusability and type flexibility.  

- Defined a template function `chkname<T>()` to handle different data types while validating or processing user input.
- Demonstrates how **templates** eliminate redundancy and support generic programming in C++.

---

## ⚙️ Technologies and Concepts Used

| Concept / Tool | Description |
|-----------------|--------------|
| 🧾 **C++ (OOP)** | Core programming language with object-oriented design |
| 🏗️ **Inheritance & Polymorphism** | Code reusability and runtime flexibility |
| 📂 **File Handling** | Reading doctor details and managing slot availability |
| ❗ **Exception Handling** | Safe input validation mechanisms |
| ⚙️ **Function Templates** | Generic, reusable function definitions |
| 💳 **Billing System** | Realistic healthcare billing simulation with insurance integration |

---

## 🧠 Program Flow

1. Choose **Inpatient** or **Outpatient**  
2. Input **patient details**  
3. Choose **doctor specialization**  
4. Fetch available **doctor and slot** from department file  
5. **Book appointment** and display confirmation  
6. Generate **billing** and validate **insurance eligibility**  

---

## 🧑‍💻 Author
<strong>Balakrishna T</strong><br>
💼 <a href="https://github.com/T-Balakrishna" target="_blank">GitHub</a> •
🌐 <a href="https://balakrishnat.vercel.app" target="_blank">Portfolio</a> •
✉️ <a href="https://mail.google.com/mail/?view=cm&to=tbalakrishna2005@gmail.com" target="_blank">Email</a>



