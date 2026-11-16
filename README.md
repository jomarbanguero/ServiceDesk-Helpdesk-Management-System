# ServiceDesk — IT Help Desk Management System

### Python | Flask | SQLite | HTML | CSS | IT Support | Cybersecurity

## Project Overview

ServiceDesk is a web-based IT Help Desk Management System developed using Python, Flask, and SQLite.

I built this project to strengthen my hands-on experience in software development, IT support operations, database management, and cybersecurity fundamentals.

The application simulates a real-world IT service desk environment where users can submit support requests and technicians can manage, prioritize, assign, and resolve tickets.

## Key Features

- **User Authentication:** Login and registration functionality with password hashing.
- **Role-Based Access:** Requester and technician accounts with different responsibilities.
- **Ticket Creation:** Submit IT incidents and support requests.
- **Ticket Management:** Track, assign, and update support tickets.
- **Priority Classification:** Low, Medium, High, and Critical.
- **Status Tracking:** Open, In Progress, and Resolved.
- **Dashboard Analytics:** View ticket totals, status statistics, and priority breakdowns.
- **Search and Filtering:** Find tickets by keyword, status, or priority.
- **Ticket Comments:** Document troubleshooting activity and updates.
- **Security Controls:** CSRF protection, password hashing, and session-based authentication.
- **Demo Data Generation:** Populate the system with fictional IT support incidents.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend development |
| Flask | Web application framework |
| SQLite | Database management |
| HTML | Website structure |
| CSS | Interface design |
| Jinja2 | Dynamic page templates |
| Git & GitHub | Version control and portfolio |


## Application Screenshots

### IT ServiceDesk Dashboard
![Dashboard](https://imgur.com/a/w0U1tCL)

### Support Ticket Management
![Ticket Management](screenshots/02-ticket-management.png)

### Create a Support Ticket
![Create Ticket](screenshots/03-create-ticket.png)

### Ticket Details and Technician Workflow
![Ticket Details](screenshots/04-ticket-details.png)

### User Authentication
![Login Page](screenshots/05-login.png)

## Technical Implementation

### Access Control and CSRF Protection
![Security Implementation](screenshots/06-security-code.png)

### Login Authentication and Password Verification
![Authentication Logic](screenshots/07-authentication-code.png)

### Dynamic Dashboard Statistics
![Dashboard Logic](screenshots/08-dashboard-code.png)

### Priority Analytics Visualization
![Priority Analytics](screenshots/09-priority-analytics-code.png)


## Security Implementation

Security was an important consideration during development.

The application incorporates password hashing to avoid storing plaintext passwords, CSRF protection for form submissions, session-based authentication, and role-based access controls.

These features helped me practice secure web development concepts while building an application relevant to IT and cybersecurity.

This project is intended for local development and demonstration, not production deployment.

## Running the Project Locally

1. Clone the repository.
2. Create a Python virtual environment.
3. Install dependencies using `pip install -r requirements.txt`.
4. Initialize the local database using the application's setup process.
5. Run `python app.py`.
6. Open `http://127.0.0.1:5000` in your browser.

Demo credentials should be configured locally rather than published as permanent application credentials.

## Skills Demonstrated

- Python backend programming
- Web application development
- SQL database operations
- IT incident and ticket management
- Authentication and access control
- Secure coding fundamentals
- Troubleshooting and debugging
- Dashboard design and data visualization
- Git and GitHub documentation

## Future Improvements

- Ticket activity logs and audit trails
- SLA tracking and resolution-time analytics
- Email notifications
- Advanced technician workload reporting
- Automated testing and continuous integration
- Deployment to a hosted demonstration environment

## Project Purpose

This project was created as a hands-on learning experience and portfolio demonstration of practical IT support, cybersecurity, and software development skills.

It reflects my interest in building tools that solve real-world technical problems while continuing to improve my programming and security knowledge.
