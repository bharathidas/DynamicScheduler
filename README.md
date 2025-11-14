## Dynamic Schedule

This module enables the creation and management of dynamic scheduler configurations directly within your Mendix application. It allows administrators to define flexible schedules, select specific days of the week, set execution times, and automatically compute the next run time—without requiring hard-coded scheduled events.
## Features:
### Dynamic Interval Scheduling
Create flexible schedules with support for:
•	Daily
•	Weekly (with multi-day selection)
•	Monthly
### Weekly Multi-Day Execution
Choose any combination of days (e.g., Mon, Wed, Fri) for repetitive microflow execution.
### Automatic Next Run Time Calculation
Automatically computes the next execution timestamp based on:
•	Start Date
•	Start Time
•	Last Run Time
•	Next Run Time
The module ensures the next run always falls on the nearest valid upcoming day.
### Execute Any Microflow
Runs any microflow dynamically by referencing its name at runtime.
### Enable/Disable Schedule
Toggle schedules without deleting them.
### Execution Insights
•	Last Run Time
•	Next Run Time
•	Last Execution Status
### User-Friendly Configuration UI
Includes a clean, intuitive configuration page for business users to manage schedules.

### Dependencies:
Mendix Modeler 10.18.4 or newer.

### Issues, Suggestions & Feature Requests
https://github.com/bharathidas/DynamicScheduler/issues

### Screenshots
<img width="1359" height="633" alt="Screenshot_2" src="https://github.com/user-attachments/assets/d4121c4c-9319-4656-8ff1-9f7b542ad4a5" />


<img width="261" height="301" alt="Screenshot_1" src="https://github.com/user-attachments/assets/8f4370dc-8f29-4ce8-b1f0-01f183f4994e" />



