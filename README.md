# CareerConnect 🎯
> A full-stack career counselling and job recommendation platform connecting students with counsellors and opportunities.

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)
![Flask](https://img.shields.io/badge/Flask-2.x-black?style=flat-square&logo=flask)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange?style=flat-square&logo=mysql)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)

---

## What is this?

CareerConnect is a multi-role web platform built to streamline career guidance for students. It supports three distinct user types — students, counsellors, and admins — each with their own dashboard, workflows, and permissions.

Built as part of an academic software engineering project at RV University.

---

## Features

### Student
- Register, login, and access a personalized dashboard
- Set and track career goals and milestones
- Book appointments with available counsellors
- Receive job and career recommendations
- Upload documents (PDF, DOC, images)
- Participate in events and webinars
- Messaging and notifications

### Counsellor
- Profile and schedule management
- View and manage student appointments
- Track counselling sessions and feedback
- Post blogs and resources for students

### Admin
- Full user management across all roles
- Analytics dashboard for platform activity
- Event and webinar management
- Resource and feedback monitoring

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Flask |
| Frontend | HTML5, CSS3, JavaScript |
| Database | MySQL |
| Auth | Werkzeug password hashing |
| Storage | File upload support (PDF, DOC, images) |
| Version Control | Git, GitHub |

---

## Project Structure

```
Career-main/
│
├── static/
│   ├── css/           # Stylesheets
│   ├── js/            # Client-side scripts
│   └── images/        # Static assets
│
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── ...            # Role-specific templates
│
├── app.py             # Main Flask application
├── models.py          # SQLAlchemy models
├── requirements.txt   # Python dependencies
├── career_counselling.sql  # Database schema
└── README.md
```

---

## Getting Started

### Prerequisites
- Python 3.10+
- MySQL 8.0+
- pip

### Installation

```bash
# Clone the repo
git clone https://github.com/Disha-cloud/career-connect.git
cd career-connect

# Install dependencies
pip install -r requirements.txt

# Set up the database
mysql -u root -p < career_counselling.sql

# Run the app
python app.py
```

Visit `http://localhost:5000` in your browser.

---

## Role-Based Access

| Role | Access |
|---|---|
| Student | Dashboard, appointments, goals, docs, jobs |
| Counsellor | Sessions, schedule, student management, blogs |
| Admin | Full platform access, analytics, user management |

---

## What I Learned

- Designing multi-role authentication with Flask Blueprints and Werkzeug
- Building relational schema for complex user relationships in MySQL
- Implementing file upload pipelines with validation and storage
- Structuring a Flask app for maintainability across 3 user modules

---

## Author

**Disha Eshwar** — [GitHub](https://github.com/Disha-cloud) · [LinkedIn](https://linkedin.com/in/disha-e)

---

*Built at RV University, Bengaluru · 2024*
