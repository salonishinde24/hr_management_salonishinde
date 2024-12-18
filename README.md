# hr_management_salonishinde
 # HR Management System

## Project Overview
The HR Management System is a web application designed to facilitate efficient human resource management. It provides two distinct dashboards: one for HR personnel and another for employees. Each dashboard is tailored to meet the specific needs of its users, ensuring seamless interaction and management of HR-related tasks.

---

## Features

### HR Dashboard
The HR dashboard is designed for managing employee-related tasks and includes the following functionalities:

1. **Daily Attendance Management:**
   - View and track the daily attendance of employees.

2. **Employee Performance Reports:**
   - Generate and view detailed performance reports of employees.

3. **Employee Leave Management:**
   - View and manage employee leave applications.

4. **Employee Profile Creation:**
   - Create and manage profiles for employees, including personal and professional details.

5. **Job Management:**
   - Post new job openings.
   - Edit existing job postings.
   - Delete job postings as required.

6. **Field Employee Enquiry Form:**
   - A dedicated form to record and manage inquiries from field employees.

### Employee Dashboard
The Employee dashboard is designed to provide employees with tools to manage their work and personal information, including:

1. **Clock-In for Attendance:**
   - Employees can record their attendance by clocking in.

2. **Leave Application:**
   - Apply for leave directly from the dashboard.

3. **Employee Information:**
   - View all personal and professional information specific to the logged-in employee.

---

## Technologies Used

- **Frontend:** React.js, React Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** MySQL
- **Additional Libraries/Tools:** Axios, Formik, Yup, SweetAlert

---

## Installation and Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/hr-management-system.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd hr-management-system
   ```

3. **Install Dependencies:**
   ```bash
   npm install
   ```

4. **Set Up the Database:**
   - Create a MySQL database.
   - Run the provided SQL script to initialize the tables.

5. **Start the Backend Server:**
   ```bash
   cd backend
   node server.js
   ```

6. **Start the Frontend Application:**
   ```bash
   cd frontend
   npm start
   ```

---

## Usage Instructions

### HR Login
- Use the HR login credentials to access the HR dashboard.
- Manage employee attendance, performance, leave, profiles, job postings, and inquiries.

### Employee Login
- Use employee login credentials to access the employee dashboard.
- Clock in for attendance, apply for leave, and view personal information.

---

## Folder Structure

```
hr-management-system/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.js
├── README.md
└── package.json
```

---

## Future Enhancements
- Add role-based access control.
- Implement real-time notifications for HR and employees.
- Enhance reporting with dynamic charts and graphs.

---

## Author
Saloni Manish Shinde

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

