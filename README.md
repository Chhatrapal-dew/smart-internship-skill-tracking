# smart-internship-skill-tracking
A web-based Smart Internship and Skill Tracking Management System for students, companies, and administrators.
🎓 Smart Internship & Skill Tracking Management System

A full-stack web-based platform designed to help students discover and apply for internships, track their applications, manage their skills, and connect with companies through a centralized system.

The platform provides separate functionality for Students, Companies, and Administrators, making internship management more organized, transparent, and efficient.

⸻

📌 Project Overview

Finding suitable internships and managing applications can be challenging for students due to scattered opportunities, limited tracking, and lack of centralized skill management.

The Smart Internship & Skill Tracking Management System addresses these challenges by providing a unified platform where students can manage their profiles and skills, explore internship opportunities, submit applications, and track their progress.

Companies can publish internship opportunities and manage applicants, while administrators can monitor and manage the overall platform.

⸻

🎯 Objectives

* Provide a centralized platform for internship opportunities.
* Allow students to create and manage professional profiles.
* Help students manage and showcase their skills.
* Enable students to search and apply for internships.
* Allow students to track their internship applications.
* Enable companies to publish and manage internship opportunities.
* Provide companies with applicant management functionality.
* Provide administrators with platform management capabilities.
* Improve communication between students and organizations.

⸻

✨ Key Features

👨‍🎓 Student Module

* Student registration and login
* Secure authentication
* Student profile management
* Skill management
* Browse available internships
* Search and explore internship opportunities
* View internship details
* Apply for internships
* Track application status
* Manage personal information

🏢 Company Module

* Company registration and login
* Company profile management
* Create internship opportunities
* Manage internship listings
* View internship applicants
* Manage applications
* Track recruitment activities

🛡️ Admin Module

* Admin authentication
* Manage students
* Manage companies
* Manage internship listings
* Monitor platform activity
* Manage users and platform data

⸻

🧠 System Highlights

The system follows a role-based architecture where different users receive functionality according to their role.

                    ┌──────────────────────┐
                    │      Application     │
                    └──────────┬───────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
        ┌───────────┐    ┌───────────┐    ┌───────────┐
        │  Student  │    │  Company  │    │   Admin   │
        └─────┬─────┘    └─────┬─────┘    └─────┬─────┘
              │                │                │
              └────────────────┼────────────────┘
                               ▼
                    ┌──────────────────────┐
                    │      Backend API     │
                    │   Node.js / Express  │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     SQLite Database  │
                    └──────────────────────┘

⸻

🛠️ Technology Stack

Frontend

* HTML5
* CSS3
* JavaScript
* Vite
* Chart.js
* Responsive UI Design

Backend

* Node.js
* Express.js
* REST API
* JWT Authentication
* bcrypt Password Hashing

Database

* SQLite

Development Tools

* Visual Studio Code
* Git
* GitHub
* npm

⸻

📂 Project Structure

Smart-Internship-Skill-Tracking/
│
├── ui/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   ├── api.js
│   │   ├── main.js
│   │   ├── router.js
│   │   └── utils.js
│   │
│   ├── index.html
│   ├── package.json
│   └── package-lock.json
│
├── server/
│   ├── db.js
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
└── README.md

⸻

🔄 Application Workflow

Student Workflow

Register / Login
       ↓
Create Profile
       ↓
Add Skills
       ↓
Browse Internships
       ↓
View Internship Details
       ↓
Apply
       ↓
Track Application

Company Workflow

Register / Login
       ↓
Create Company Profile
       ↓
Post Internship
       ↓
Receive Applications
       ↓
Review Applicants
       ↓
Manage Applications

Admin Workflow

Admin Login
     ↓
Dashboard
     ↓
Manage Users
     ↓
Manage Companies
     ↓
Manage Internships
     ↓
Monitor Platform

⸻

🔐 Authentication & Security

The application includes authentication and authorization mechanisms for different user roles.

Key security features include:

* User authentication
* JWT-based authorization
* Password hashing using bcrypt
* Role-based access control
* Protected API routes
* Environment-based configuration support

Note: Production deployments should use secure environment variables for sensitive credentials and secrets.

⸻

🚀 Getting Started

Prerequisites

Make sure the following are installed on your system:

* Node.js
* npm
* Git

⸻

📦 Installation

1. Clone the Repository

git clone https://github.com/Chhatrapal-dew/smart-internship-skill-tracking.git

2. Navigate to the Project

cd YOUR-REPOSITORY

⸻

▶️ Running the Backend

Navigate to the server directory:

cd server

Install dependencies:

npm install

Start the backend:

npm start

The backend server will run on the configured local port.

⸻

💻 Running the Frontend

Open another terminal and navigate to the UI directory:

cd ui

Install dependencies:

npm install

Start the development server:

npm run dev

Vite will provide a local development URL, usually:

http://localhost:5173

⸻

🗃️ Database

The application uses SQLite as its database.

Database initialization and table creation are handled through the backend database module.

The database stores information related to:

* Users
* Students
* Companies
* Internships
* Applications
* Skills
* Other application-related data

⸻

📊 Main Modules

Module	Description
Authentication	User registration and login
Student Management	Student profile and skill management
Company Management	Company profiles and internship postings
Internship Management	Create, browse and manage internships
Application Management	Apply and track internship applications
Skill Management	Add and manage student skills
Admin Management	Platform administration
Dashboard	Overview and activity monitoring

⸻

🎨 User Interface

The application is designed with a clean and responsive interface focused on usability and simple navigation.

The frontend follows a component-based structure to make the application easier to maintain and extend.

⸻

🔮 Future Enhancements

Future versions of the project can include:

* 🤖 AI-based internship recommendations
* 🧠 AI-powered skill gap analysis
* 📄 AI resume analysis
* 🎯 Personalized career recommendations
* 📊 Advanced student analytics
* 📈 Internship market analytics
* 🔔 Email and notification system
* 📱 Mobile application
* ☁️ Cloud deployment
* 🔗 LinkedIn profile integration
* 📑 Resume generation
* 🧩 Skill-based internship matching

⸻

🧪 Project Status

Status: 🚧 Development / Academic Project

The current version provides the core functionality for managing students, companies, internships, skills, and applications.

Additional features and improvements may be added in future versions.

⸻

🎓 Academic Project

This project was developed as an academic full-stack web development project with the objective of applying concepts related to:

* Web Development
* Database Management
* Software Engineering
* REST APIs
* Authentication
* Full-Stack Application Development
* User Interface Design

⸻

👨‍💻 Author

Chhatrapal Dewangan

B.Tech Computer Science / Engineering Student

⸻

📄 License

This project is developed for educational and academic purposes.

You may modify and extend the project for learning and development purposes.

⸻

⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.
