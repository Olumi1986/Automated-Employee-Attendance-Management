# Automated Employee Attendance Management System

## 📌 Project Overview

The Automated Employee Attendance Management System is a workflow automation project built with **n8n, Docker, and Google Sheets**.

The system automates the process of capturing employee attendance information, evaluating attendance time, determining whether an employee is **Present or Late**, and recording the result in Google Sheets.

The project demonstrates how workflow automation can be used to simplify repetitive administrative processes and improve data recording.

## 🎯 Project Objective

The objective of this project is to automate a basic employee attendance process that would otherwise require manual data entry and classification.

The workflow captures employee information, processes attendance time, applies conditional logic, and automatically sends the resulting attendance record to Google Sheets.

## ⚙️ How the Workflow Works

The workflow follows this process:

**Attendance Trigger → Capture Employee Details → Get Current Time → Check Attendance Time → Present/Late → Google Sheets**

### Workflow Steps

1. **Employee Attendance Register**
   - Initiates the attendance workflow.

2. **Employee Details Node**
   - Captures employee ID, name, department, email, date, check-in time, and attendance status.

3. **Current Time**
   - Provides the time parameters used for attendance evaluation.

4. **IF Node**
   - Applies conditional logic to determine the appropriate attendance status.

5. **Present / Late**
   - Classifies the employee based on the attendance condition.

6. **Google Sheets**
   - Automatically records the attendance information.

## 🛠️ Technologies Used

- **n8n** – Workflow automation
- **Docker** – Containerized deployment of n8n
- **Google Sheets** – Attendance data storage
- **Conditional Logic** – Attendance classification
- **JSON** – Workflow configuration and data representation

## 🚀 Key Features

- Automated attendance processing
- Employee information capture
- Time-based attendance classification
- Present/Late decision logic
- Automated Google Sheets integration
- Docker-based n8n environment
- Structured workflow design

## 📸 Project Screenshots

### n8n Workflow

![n8n Workflow](n8n-workflow.png)

### Docker Desktop

![Docker Desktop](docker-n8n.png)

### Google Sheets Output

![Google Sheets Output](google-sheets-result.png)

## 📚 Skills Demonstrated

- Workflow Automation
- Business Process Automation
- n8n
- Docker
- Google Sheets Integration
- Conditional Logic
- Data Management
- Process Design
- Low-Code Automation

## 💡 Project Learning

This project provided practical experience in designing an end-to-end automation workflow, connecting different services, applying business logic, and producing a usable data output.

It also strengthened my understanding of how automation tools can be applied to repetitive administrative and data-processing tasks.

## 👨‍💻 Author

**Wole**

Computer Science | Data & ICT | Workflow Automation | AI Automation
