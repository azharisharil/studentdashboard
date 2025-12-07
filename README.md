# UiTM Student Portal (Student Dashboard)

This project is a front-end web application prototype designed to simulate a Student Management Portal. It demonstrates a responsive user interface with simulated authentication and data visualization.

UNIVERSITI TEKNOLOGI MARA (UiTM)
FACULTY OF INFORMATION SCIENCE 
BACHELOR OF INFORMATION SCIENCE (HONS.)
INFORMATION SYSTEMS MANAGEMENT(CDIM262)

ADVANCED WEB DESIGN DEVELOPMENT AND CONTENT MANAGEMENT (IMS566)

PAIRING ASSIGNMENT: 
STUDENT DASHBOARD SYSTEM

PREPARED BY: 
MUHAMMAD NOOR AZHARI BIN SHARIL (2025305961)

AHMAD NUR SYAFIQ BIN AHMAD KAMAL AFFENDI (2022882696)

GROUP:
CDIM2624A

PREPARED FOR:
DR. MUHAMMAD ASYRAF BIN WAHI ANUAR

SUBMISSION DATE:
7 DECEMBER 2025


## 📂 Deliverables

### 6.1. Live Website Link (GitHub Pages)
👉 **[CLICK HERE TO VIEW LIVE SITE]( https://azharisharil.github.io/studentdashboard/)**


### 6.2. GitHub Repository Link
👉 **[CLICK HERE TO VIEW SOURCE CODE](https://github.com/azharisharil/studentdashboard.git)**


---

## 📝 6.3. Documentation

### a. Project Description
The **UiTM Student Portal** is a dashboard system designed for students to manage their academic activities. It features a responsive Sidebar layout that works on both desktop and mobile devices. The system allows students to view analytics (CGPA, Attendance), register/drop courses, manage assignment submissions, and view group members.

### b. Features Included
1.  **Responsive Dashboard:** Uses Chart.js to visualize CGPA, Credit Hours, and Attendance.
2.  **Sidebar Navigation:** A persistent sidebar for easy navigation between modules (Dashboard, Courses, Assignments, Students).
3.  **Course Management:** Ability to simulate registering new courses and dropping existing ones via DOM manipulation.
4.  **Assignment Tracking:** Users can add new assignments and track their status (Pending, Submitted, Overdue).
5.  **Group Member Management:** Users can add group members, with automatic avatar generation based on names.
6.  **Dark/Light Mode:** Theme toggle that persists user preference using LocalStorage.
7.  **Mobile Friendly:** Sidebar collapses into a hamburger menu on smaller screens.

### c. Instructions to Test Login (Simulation)
Since this is a front-end prototype, no backend database is connected. Please use the following **hardcoded credentials** to simulate a successful login:

| Field | Value |
| :--- | :--- |
| **Student ID** | `2025123456` |
| **Password** | `123456` |

> **Note:** Entering incorrect credentials will trigger an error alert. Clicking "Register Now" will open a modal displaying these credentials.

### d. Frameworks & Libraries Used
The project utilizes the following technologies via CDN:

* **HTML5 & CSS3:** Core structure and styling.
* **Bootstrap 5.3.3:** For responsive layout (Grid system), components (Modals, Cards, Navbar), and styling.
* **Bootstrap Icons:** For user interface icons.
* **Chart.js:** For rendering interactive data visualization (Doughnut and Bar charts).
* **Google Fonts (Poppins):** For typography.
* **Vanilla JavaScript:** For logic handling (Authentication simulation, DOM manipulation, LocalStorage).

---

© 2025 Universiti Teknologi MARA (UiTM) Faculty of Information Science
