Problem Statement — Event Management System in Salesforce

Managing events manually is time-consuming and error-prone. Event organizers face challenges such as:
	1.	RSVP & Attendee Tracking
	•	Difficult to confirm attendees, handle cancellations, and manage waitlists when sessions reach full capacity.
	2.	Payment Management
	•	No automated reminders for pending payments.
	•	Manual tracking of who has paid and who hasn’t causes delays and errors.
	3.	Venue & Schedule Conflicts
	•	Overlapping sessions or double-booked venues often go unnoticed until late in the planning stage.
	4.	Communication Gaps
	•	Attendees often miss important updates such as confirmation, waitlist status, or payment reminders.
	5.	Reporting & Insights
	•	Event planners lack visibility into session attendance, vendor costs, and overall revenue vs. expenses.

⸻

🎯 Goal of the Project

To build a Specialized Event Management Application on Salesforce that automates the end-to-end lifecycle of event planning and management, including:
	•	RSVP Confirmation & Waitlist Handling → Automatically manage attendee status based on session capacity.
	•	Payment Tracking & Reminders → Create payment records, send automated reminders before due dates.
	•	Venue Conflict Detection → Prevent scheduling two sessions at the same venue and time.
	•	Automated Email Notifications → Confirmations, waitlist alerts, and payment reminders.
	•	Reports & Dashboards → Give organizers real-time insights into revenue, expenses, and attendance.

⸻

👉 This system reduces manual effort, avoids human errors, and provides a professional, automated experience for both organizers and attendees.# Specialized-Event-Management-System
Salesforce Capstone Project - Specialized Event Management System
## 📌 Project Overview
The Specialized Event Management System is a Salesforce-based application that helps manage events such as weddings, conferences, and corporate gatherings...

## 🎯 Objectives
- Automate event planning, scheduling, and coordination
- Track budgets, vendors, and payments in real time
- Improve attendee management with RSVP and feedback system
- Provide dashboards for event insights

## 🛠️ Tech Stack
- Salesforce (Custom Objects, Flows, Reports, Dashboards)
- Experience Cloud (for external attendees)
- GitHub (documentation & project files)

## 📂 Repository Structure
- /docs → Documentation (overview, problem statement, diagrams)
- /config → Configuration details (objects, relationships, flows)
- /presentation → Project presentation and report

## 👥 Users
- Event Planner (Admin)
- Vendor Manager
- Finance Manager
- Attendee Manager
- Attendees (via portal)

## 📊 ERD
![ERD Diagram](docs/ERD.png)

## 🚀 How to Run
1. Clone this repository
2. Import metadata/configuration into your Salesforce Developer Org
3. Test with sample data (events, sessions, vendors, attendees)
