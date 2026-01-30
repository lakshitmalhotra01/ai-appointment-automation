# Dr. Strange – AI Appointment Automation

## 📌 Overview
This project automates physiotherapy appointment scheduling for a clinic using **n8n**.  
It handles appointment booking, availability checks, logging, and email confirmations.

## 🛠️ Tech Stack
- n8n
- Google Calendar API
- Google Sheets API
- Gmail API

## ⚙️ Workflow Features
- Accepts patient details (name, email, date, time)
- Checks doctor availability from Google Calendar
- Creates appointment events automatically
- Logs appointment data into Google Sheets
- Sends email confirmation to patients

## 🧩 Workflow Structure
1. Manual Trigger
2. Edit Fields (Patient Input)
3. Get Existing Calendar Events
4. Create Calendar Event
5. Append Appointment Data to Google Sheets
6. Send Confirmation Email

## 📸 Screenshots
Screenshots are available in the `screenshots/` folder showing:
- n8n workflow
- Google Calendar booking
- Google Sheets logging
- Email confirmation

## 🚀 How to Run
1. Import the workflow JSON into n8n
2. Connect Google Calendar, Sheets, and Gmail credentials
3. Execute the workflow with patient details

## 👨‍💻 Author
Intern Project – Appointment Automation using n8n
