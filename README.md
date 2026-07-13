# NGO Management System

A web-based management system developed to support non-governmental organizations (NGOs) in organizing volunteers, donations, and community activities. The application provides separate interfaces for administrators, volunteers, donors, and organization staff, enabling efficient management of daily operations through a centralized platform.

---

## Features

### User Authentication

- Secure user registration and login
- Password hashing for user credentials
- Session-based authentication
- Role-based access control

### Volunteer Management

- Volunteer registration
- Profile management
- View available activities
- Track participation requests

### Donation Management

- Submit donations
- View donation history
- Manage donation records
- Track donation status

### Organization Management

- Create and manage NGO activities
- Review volunteer applications
- Manage donation requests
- Update organization information

### Administration

- Manage users
- Monitor system activity
- Approve or reject requests
- Maintain platform data

---

# Tech Stack

### Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend

- PHP

### Database

- MySQL

---

# Project Structure

```text
.
├── admin/
├── css/
├── database/
├── images/
├── includes/
├── js/
├── pages/
├── user/
├── organization/
├── volunteer/
├── index.php
└── README.md
```

---

# Core Functionality

The system allows different user roles to interact through a unified platform.

- Users can create accounts and log in securely.
- Volunteers can browse and participate in NGO activities.
- Donors can submit and manage donations.
- Organizations can create events and manage volunteers.
- Administrators oversee the entire platform and maintain system integrity.

---

# Installation

## Requirements

- PHP 8.x
- MySQL
- Apache (XAMPP, WAMP, or Laragon)

---

## Setup

Clone the repository

```bash
git clone <repository-url>
```

Move the project into your web server directory.

Example (XAMPP):

```text
htdocs/
```

Import the provided SQL database into MySQL.

Update the database configuration file if necessary.

Run the project from

```text
http://localhost/project-folder
```

---

# Technologies Demonstrated

- PHP Web Development
- MySQL Database Design
- CRUD Operations
- Session Management
- Authentication & Authorization
- Role-Based Access Control
- Relational Database Design
- Responsive Web Design

---

# Future Improvements

- Email verification
- Password recovery
- Notification system
- Advanced search and filtering
- Dashboard analytics
- REST API integration
- File upload improvements
- Docker deployment

---

# Screenshots

Application screenshots can be added in a `screenshots/` directory.

Example:

```text
screenshots/
├── home.png
├── login.png
├── volunteer-dashboard.png
├── organization-dashboard.png
└── admin-panel.png
```
