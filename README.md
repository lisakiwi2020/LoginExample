# COMP639 Individual Web Application

## System Description

This web application is a cleanup event management system developed using Python and Flask.
The system allows users to register accounts, log in securely, and access different functions depending on their user role.
The application supports the organisation and management of environmental cleanup events, including event registration, volunteer participation, feedback submission, and administrative reporting.
The system implements role-based access control, ensuring that different users have access to appropriate features.
Live Application:
https://lisakiwi2026.pythonanywhere.com

---

## User Roles

The system supports three types of users:

Customer / Volunteer

  - Can register an account through the web interface
  
  - Can browse and filter available cleanup events
  
  - Can register for events
  
  - Can view their registered events
  
  - Can submit feedback after attending events

Staff / Event Leader

  - Can create new cleanup events
  
  - Can edit existing events
  
  - Can generate event reports

Admin

  - Can manage all events
  
  - Can view and search all users
  
  - Can view individual user profiles
  
  - Can update user roles

- Can view system statistics and reports
---


## Database Data

The database is pre-populated with sample data:

| Data Type | Quantity |
|-----------|----------|
| Customers / Volunteers | 20 |
| Staff / Event Leaders | 5 |
| Admin Users | 2 |
| Cleanup Events | 20 |
| Event Registrations | 20 |

Staff and Admin accounts are created directly in the database for management purposes.

---

## Test Login Accounts

The system includes pre-configured accounts for testing different user roles.

### Admin Accounts
| Username | Password |
|---------|---------|
| admin1 | admin1pass |
| admin2 | admin2pass |

### Staff / Event Leader Accounts
| Username | Password |
|---------|---------|
| staff1 | staff1pass |
| staff2 | staff2pass |
| staff3 | staff3pass |
| staff4 | staff4pass |
| staff5 | staff5pass |

### Customer / Volunteer Accounts
| Username | Password |
|---------|---------|
| customer1 | customer1pass |
| customer2 | customer2pass |
| customer3 | customer3pass |
| customer4 | customer4pass |
| customer5 | customer5pass |

Customers can also create new accounts using the **Sign Up** page.
---

## Main Features

- User registration
- Secure login system
- Role-based access control
- Event registration system
- User profile page
- Logout functionality
- PostgreSQL database integration
- Deployment on PythonAnywhere

---

## Technologies Used

- Python
- Flask
- PostgreSQL
- HTML
- Flask-Bcrypt
- PythonAnywhere
- GitHub

---

## How to Run the Application

1. Clone the GitHub repository
2. Install the required packages
3. Create the database using
4. Populate the database using
5. Update database connection settings in `connect.py`
6. Run the application

---

## AI Declaration

ChatGPT was used as a learning and debugging assistant during this project. 
It helped explain programming concepts, suggest example code, and identify errors. 
All final design decisions, testing, and integration were completed by Lisa Lin.
