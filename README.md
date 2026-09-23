# Smart Parent–Student Visitation Management System

*A web-based system designed to improve the management of parent and student visits at Blue Lakes International School. The system replaces the traditional manual visitor register with a digital platform for recording visitor information, verifying parents or guardians, requesting and managing visits, monitoring student movement, and generating visitation reports. The system aims to improve operational efficiency, security, accountability, and accessibility of visitation records within the school.*

## Features

* **Parent/Guardian Registration:** Allows parents and guardians to provide and maintain their relevant visitor information.

* **About the Student/Student Information:** Enables authorized school staff to access relevant student information and identify the student being visited.

* **Visitor Registration:** Digitally records visitor details, purpose of the visit, date, arrival time, and departure time.

* **Visitor Verification:** Supports verification of parents or guardians before they are allowed to visit a student.

* **Visit Approval:** Allows authorized school staff to approve or reject visitation requests.

* **Student Movement Monitoring:** Helps the school monitor when students leave their normal activities to meet authorized visitors.

* **Check-In and Check-Out:** Records the time a visitor enters and leaves the school.

* **Digital Records:** Stores visitation information electronically for easier retrieval and record management.

* **Reports:** Generates visitation reports that can help school management monitor visits and improve decision-making.

* **User Management:** Provides controlled access for authorized users such as administrators and relevant school staff.

* **Security and Accountability:** Reduces reliance on manual registers and provides traceable digital records of visitors and visits.

## How to run this project

The Smart Parent–Student Visitation Management System is developed as a web-based application and can be run locally using a PHP development environment such as **XAMPP**.

The project can be accessed through a local web server after installing XAMPP and placing the project folder inside the `htdocs` directory.

For example:

```text
http://localhost/parent_visit_system/
```

The system is developed as a case study for **Blue Lakes International School**.

### Prerequisites

Before running the project, users should install:

* XAMPP
* Apache Web Server
* MySQL
* PHP
* A modern web browser such as Google Chrome, Microsoft Edge, or Mozilla Firefox
* Visual Studio Code or another suitable code editor
* Git, if the project is cloned from GitHub

### Installation

**1. Clone the repository:**

Run the following command in Command Prompt, PowerShell, or Terminal:

```bash
git clone https://github.com/YOUR-GITHUB-USERNAME/Smart-Parent-Student-Visitation-Management-System.git
```

**2. Move the project into XAMPP:**

Copy the project folder into:

```text
C:\xampp\htdocs\
```

The resulting folder structure should be similar to:

```text
C:\xampp\htdocs\parent_visit_system\
```

**3. Start XAMPP services:**

Open the XAMPP Control Panel and start:

* Apache
* MySQL

**4. Create the database:**

Open phpMyAdmin through:

```text
http://localhost/phpmyadmin/
```

Create the required database and import the project's SQL database file, if provided.

**5. Configure the database connection:**

Open the project's database configuration file and enter the appropriate database details, such as:

```text
Database Host: localhost
Database Username: root
Database Password: 
Database Name: parent_visit_system
```

**6. Run the system:**

Open a web browser and enter:

```text
http://localhost/parent_visit_system/
```

The system should then display the login or home page.

## License

This project is developed primarily for **academic and educational purposes** as part of an Information Technology research and capstone project.

The project may be studied and modified for educational purposes. However, the system's source code, documentation, database structure, personal information, school information, and other original materials should not be reproduced, redistributed, or presented as another person's work without appropriate permission and acknowledgement.

The project is provided for academic demonstration and research purposes and does not provide any warranty regarding its suitability for production use.

For the complete licensing terms, see the [`License.txt`](License.txt) file in this repository.

## Contributors

* **Joseph Ndikumana** – Project Developer and Researcher
* **Blue Lakes International School** – Case Study Institution

## Project Link

**Project Link:** https://github.com/YOUR-GITHUB-USERNAME/Smart-Parent-Student-Visitation-Management-System

## Case Study

**Blue Lakes International School (BLIS)**

The system is designed based on the visitation management needs of Blue Lakes International School, where the traditional manual visitor registration process can be improved through digital technology.

## Technologies Used

* **PHP** – Server-side application development
* **MySQL** – Database management
* **HTML5** – Web page structure
* **CSS3** – Interface design
* **JavaScript** – Client-side functionality
* **XAMPP** – Local development environment
* **Git & GitHub** – Version control and project repository

## Project Objectives

The system is intended to:

1. Digitize the parent and visitor registration process.
2. Improve the verification and approval of school visitors.
3. Monitor student movement during approved visits.
4. Reduce dependence on manual visitor registers.
5. Improve the security and accountability of visitation records.
6. Provide accurate and accessible visitation reports.
7. Improve operational efficiency in managing parent–student visits.

## Future Improvements

Future versions of the system may include:

* SMS or email notifications
* QR-code visitor identification
* Student ID card integration
* Automated parent appointment scheduling
* Face recognition for authorized visitors
* Mobile application integration
* Real-time notifications to responsible staff
* Advanced analytics and dashboards
* Cloud-based deployment
* Enhanced role-based access control

## Academic Integrity

This project is developed for academic and research purposes. Any use of AI tools or external resources during development should be reviewed, edited, tested, and properly acknowledged where required. The student remains responsible for the accuracy, originality, functionality, and compliance of the final submitted project.
