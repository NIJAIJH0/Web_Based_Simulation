📘 MCQ Examination System
(Student • Staff • Admin - Web Based Online Exam Platform)

A full-featured online MCQ (Multiple Choice Questions) examination system with three different panels:

Student → Attend exams, view results

Staff → Create questions & schedule exams

Admin → Manage system, users, approvals

✨ Features
🧑‍🎓 Student Panel

Register & Login authentication

Dashboard with upcoming & completed exams

Exam instructions & timed MCQ test

Auto-submit when timer ends

Instant score calculation

View previous results

🧑‍🏫 Staff Panel (Examiners)

Create & manage question banks

Upload MCQs using Excel/CSV

Create exams with schedule + duration

Negative marking options

Assign exams to batches/subjects

View student performance analytics

🛠 Admin Panel

Manage users: Add/Block/Role assign

Manage subjects, classes & departments

Approve/publish exams created by staff

Full system log and analytics

🧩 System Architecture

🎯 Role-based access control
🗄 Centralized database for exam & results
⏳ Front-end exam handling with timer script
🔐 Secure login & session management

🗄 Database Structure (Core Tables)
Table Name	Description
users	user_id, name, email, password, role
subjects	subject_id, name, department
classes	class_id, batch/year mapping
user_class_map	map students to classes
questions	MCQ data: text, options, correct answer
exams	schedule, duration, negative marking
exam_question_map	questions linked to exam
results	score, status
answers	saved student responses

Full SQL dump provided in /database/db.sql (when implemented)

🛠 Tech Stack (Configurable)
Layer	Option A (Default)
Frontend	HTML, CSS, Bootstrap, JavaScript
Backend	PHP / Node.js / Django (selectable)
Database	MySQL
