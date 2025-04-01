Overview

This AngularJS controller (HomeCtrl.js) manages a fitness or gym membership interface. It provides functionalities for:
	•	Viewing member data
	•	Adding new members
	•	Logging daily workouts
	•	Recording attendance
	•	Switching between different UI tabs

It interacts with backend APIs using AJAX calls and updates the UI accordingly.

Features

1. View Member Data

Fetches and displays a list of all members from the backend (GET /memberData).

2. Add Member

Sends new member data to the backend (POST /addMember).

3. Add Daily Workout

Records daily workout progress for members (POST /addDailyWorkout).

4. Add Attendance

Records attendance for a selected member (POST /addAttendance).

5. UI Menu Switching

Toggles between:
	•	Member Registration
	•	Workout Review
	•	Attendance Management

Uses jQuery to control the visibility of different sections.

Setup Instructions
	1.	Include this controller in your AngularJS app.
	2.	Ensure jQuery is included in your HTML since this controller uses jQuery for DOM manipulation.
	3.	Make sure the backend API routes (/memberData, /addMember, /addDailyWorkout, /addAttendance) are implemented.

Dependencies
	•	AngularJS
	•	jQuery

Author
Bhavitha
