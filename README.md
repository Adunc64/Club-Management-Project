# Club-Management-Project
A university club management website built using PHP for the backend, MySQL for the database, and HTML/CSS for the frontend.

Website Overview

The system includes **six different user views**, each with tailored features and permissions:

1. No View (Public/Guest)
2. Member View
3. Panel View
4. Advisor View
5. OCA View
6. Department View
7. Sponsor View

# Authentication
- Login/Logout
- "Sign Up" for Members and Sponsors

---

# Project Structure

- `dbconnect.php` – Handles all database connections. **Do not edit.**
- `navbar.php` – Contains the navigation bar and alert system. **Editable.**
- Remaining files – Application logic and view pages. **Not to be modified.**
- Custom files – You may add your own files to the repo and link them using `include("dbconnect.php")` and `include("navbar.php")`.

---

# Features by View

=> No View
- `index.php` – Landing page
- Login / Logout
- Signup (for members and sponsors)
- Navbar with dynamic alerts

=> Member View
- View announcements for their club and department
- Access to:
  - Club Events
  - Club Panel Members
  - All Events, Departments, Clubs, Advisors
  - Personal Profile

=> Panel View
- Same as Member View plus:
  - View & manage club members
  - Approve/Reject membership and sponsorship requests
  - Submit club event requests
  - Edit own profile

=> Advisor View
- View all department announcements
- Manage:
  - Club events (Announce/Conclude)
  - Club members and panel
  - Approve club event requests
  - Make announcements to departments

=> OCA View
- Highest level of control
- Full access to all clubs and departments
- Approve/Decline event and sponsorship requests
- Allocate funds
- Edit data for clubs, panels, members, sponsors
- Manage fund balance

=> Department View
- View and manage clubs and announcements for their department
- Edit clubs, panels, members, advisors under their department

=> Sponsor View
- View all event details
- Fund club events
- Edit own profile and sponsorship data

---

# Getting Started

1. Clone the repository.
2. Import the database SQL file into your MySQL server.
3. Update database credentials in `dbconnect.php` (if needed).
4. Run the project on a local server (e.g., XAMPP, WAMP, etc.).
5. Log in using different roles to explore features.

---

# Notes

- Always use `include("dbconnect.php")` and `include("navbar.php")` in new files for consistent database access and navigation.
- **Do not modify** `dbconnect.php` and core application logic files (marked in yellow).
- Feel free to contribute your own modules or features by adding new files and linking them via the navbar.

---

# Screenshots

> *[Add screenshots here to visually explain different views]*

