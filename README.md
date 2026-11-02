# SAPA – Student Academic Performance Analytics System

A web-based Student Academic Performance Analytics System developed as a B.Tech Computer Science and Business Systems (CSBS) micro project.

SAPA helps manage student academic records, monitor performance, analyze attendance and generate academic reports through a simple and user-friendly dashboard.

## Project Overview

The Student Academic Performance Analytics System is designed to simplify student record management and academic performance monitoring.

The system combines a web-based frontend with a C++ backend and CSV-based student data storage.

## Features

- **Dashboard:** Displays student statistics and recent academic records.
- **Student Management:** Add, search and manage student records.
- **Academic Analytics:** Visualize student performance using charts and graphs.
- **Attendance Analysis:** Monitor student attendance percentages.
- **Reports:** View academic performance reports and print records.
- **Subject-wise Analysis:** Analyze marks across different subjects.

*Note: Features are subject to the functionality implemented in the current backend.*

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Webpage structure |
| CSS3 | Styling and responsive design |
| JavaScript | Frontend functionality |
| C++ | Backend development |
| CSV | Student data storage |
| Chart.js | Data visualization |

## Project Structure

```text
SAPA-Student-Analytics/
│
├── server.cpp
├── student.csv
│
├── public/
│   ├── index.html
│   ├── student.html
│   ├── analytics.html
│   ├── reports.html
│   ├── about.html
│   │
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       ├── dashboard.js
│       └── student.js
│
├── README.md
├── .gitignore
├── LICENSE
└── CONTRIBUTING.md
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/SAPA-Student-Analytics.git
```

### 2. Open the project folder

```bash
cd SAPA-Student-Analytics
```

### 3. Install a C++ compiler

Install MinGW-w64 or another compatible C++ compiler.

Check the compiler:

```bash
g++ --version
```

### 4. Configure backend dependencies

Make sure the header files and libraries required by `server.cpp` are installed and available.

### 5. Compile the server

Use the compilation command appropriate for the dependencies and configuration in `server.cpp`.

### 6. Run the server

```bash
./server
```

On Windows, the executable may be named `server.exe`.

### 7. Open the application

Visit:

```text
http://localhost:8080
```

The server must be running while using the application.

## Application Pages

| Page | Description |
|---|---|
| Dashboard | Overall academic summary |
| Students | Student record management |
| Analytics | Graphical academic analysis |
| Reports | Academic reports |
| About | Project information |

## Data Storage

Student records are maintained in a CSV file named `student.csv`.

The application can use this file to store and retrieve student academic information through the C++ backend.

## Project Objectives

1. Simplify student academic record management.
2. Monitor student performance.
3. Analyze subject-wise academic results.
4. Track student attendance.
5. Present academic information through graphical reports.

## Future Enhancements

- Student login and authentication.
- Database integration using MySQL.
- Export reports to PDF.
- Advanced performance prediction.
- Semester-wise performance comparison.
- Improved data visualization.

## Academic Information

**Project Name:** Student Academic Performance Analytics System (SAPA)

**Course:** B.Tech Computer Science and Business Systems (CSBS)

**Project Type:** Micro Project

## Author

Developed as an academic micro project.

---

**SAPA – Making Student Performance Analysis Simpler.**
