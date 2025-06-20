# Course Registration Website

A dynamic, user-friendly web application to simplify and streamline the course registration process for students at VIT Chennai.

## Developed By
- Lavanya (23BPS1086)  
- Shreyasee (23BPS1124)  
- Harshini (23BPS1156)  

## Introduction

The traditional course registration process often suffers from inefficiencies such as:

- Time-consuming manual workflows  
- Scheduling conflicts  
- Delays in seat availability updates  
- Errors while managing timetables  

To resolve these issues, this project introduces a seamless web-based platform allowing students to:

- Search and filter courses in real-time  
- Dynamically manage their timetable  
- View instant seat availability updates  
- Register for courses with automatic conflict checks  

## Technology Stack

| Layer       | Tools / Languages           |
|------------|-----------------------------|
| Frontend   | HTML, CSS, JavaScript, React.js |
| Backend    | Node.js                     |
| Database   | Oracle (SQL Plus)           |
| Tools      | Git, GitHub                 |

## Application Flow Diagram

1. User accesses the Login Page  
2. Login credentials are sent to the Node.js backend  
3. Credentials are validated against Oracle DB  
4. If valid, the user is redirected to the Course Search Page  
5. User searches courses by code/name, server fetches availability  
6. Course details are displayed on the frontend  
7. Timetable is generated dynamically  
8. Course registration updates Oracle DB in real-time  

## Key Features and Functionalities

### User Authentication
- Login using registration number and password
  
### Course Search and Filtering
- Search by course code or name  
- Dynamic filtering options for efficient discovery  

### Interactive Timetable Management
- Split-screen interface: view timetable and course list side-by-side  
- Automatic updates to timetable on course add/drop  

### Real-Time Data Synchronization
- Auto-refresh mechanism for seat availability  
- Prevents double-booking and over-enrollment  

### User Interface and Experience
- Responsive design for all device sizes  
- Toggle for dark mode and light mode  

## Thank You

Developed as part of the academic curriculum at VIT Chennai.
