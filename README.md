# 🚀 KuttyHack Series: The n8n Edition

![Event Banner](./assets/banner.png)

# Title: [Dhrithi - Smart Doubt Solving]

---

### Team Members
* **Member 1:** [Giridhar H S / https://github.com/giridharhspoojappura-lang]
* **Member 2:** [Adithyan S / https://github.com/adithyan-s-369]
* **Member 3:** [Elesh G Krishnan / https://github.com/eleshgkrishnan-dev]
---

### Link to product walkthrough
[[Insert Link to Video (YouTube/Drive)](https://drive.google.com/file/d/1uHvR5B7ARUqBck7xS8Qvg8yzcd1BHa6m/view?usp=sharing)]

---

### How it Works?

#### 1. Explaining the working of project
[Project Flow
This project is an Anonymous Smart Doubt Redirection System built using n8n.
A student submits a doubt through a form.
The system keeps the student’s identity anonymous.
AI detects the subject of the doubt.
Based on the subject, the system selects a teacher from a Google Sheet.

🔁 Round Robin Feature

If multiple teachers handle the same subject:
The system assigns the doubt using a Round Robin algorithm.
The teacher with the least number of assigned doubts is selected.
After assignment, their counter increases.
This ensures fair workload distribution.
The teacher receives the doubt by email.
They respond using a link.
The response is automatically saved in Google Sheets..]

#### 2. Embed video of project demo
[https://drive.google.com/file/d/1uHvR5B7ARUqBck7xS8Qvg8yzcd1BHa6m/view?usp=sharing]
---

### Libraries
[n8n Workflow Automation

Google Sheets

Gmail Integration

Gemini 2.5 Flash AI Model

JavaScript (for routing + logic)]

---

### How to configure
[Update the Teacher Sheet with:
Teacher Name
Subject
Email ID
Connect:
Google Sheets credentials
Gmail credentials
Gemini API key
Activate both workflows:
Student Submission Workflow
Teacher Reply Workflow]

---

### How to run
[Open the Student Form link.
Submit a doubt.
Check:
Teacher email (doubt received)
Google Sheet (entry created)
Teacher clicks the link and submits answer.
Answer appears in the sheet automatically.]

---

