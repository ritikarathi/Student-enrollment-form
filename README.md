Student Enrollment Form – Micro Project

This project is a simple web-based Student Enrollment Form that performs Create and Update operations using JSONPowerDB (JPDB) as the backend database.
It follows all rules of data validation, primary key handling, and form control enabling/disabling.

⭐ Project Overview

The form stores data in STUDENT-TABLE of the SCHOOL-DB database.
It works with three control buttons:

Save – Inserts data when Roll-No (primary key) does not exist
Update – Updates data when Roll-No already exists
Reset – Clears and resets the form

The form always starts with Roll-No enabled and all other fields + buttons disabled.

🧾 Input Fields
The form uses the following fields:
Roll-No (Primary Key)
Full-Name
Class
Birth-Date
Address
Enrollment-Date

🎯 Features
Roll-No based search using JPDB
Validates empty fields
Smart form control enabling/disabling
Insert new student data
Update already existing student data
Auto-focus logic for better UX
Works without backend server (uses JPDB API)

🛠️ Tech Stack
HTML5
CSS3
JavaScript
JSONPowerDB (JPDB)
jQuery

🗂️ Database Details
Database: SCHOOL-DB
Table: STUDENT-TABLE
Primary Key: Roll-No

🔗 JPDB API Used
GET_BY_KEY → Check if Roll No exists
PUT → Save new data
UPDATE → Update existing data

🚀 How the Project Works
On page load → Only Roll-No field is enabled
User enters Roll-No

System checks:
If Roll-No does not exist → Enable Save + Reset
If Roll-No exists → Show data, enable Update + Reset
User enters remaining fields
Click Save or Update
Form resets automatically

📁 Project File Structure
student-enrollment/
│── index.html
│── script.js
│── README.md

👩‍💻 Author
Ritika Rathi
Student – Computer Science
Micro Project on JSONPowerDB
