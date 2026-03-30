#  Design Document – Event Management System

## 1. System Architecture

The system follows a **three-tier architecture**:

1. Presentation Layer (Frontend)
2. Application Layer (Backend)
3. Data Layer (Database)

---

## 2. Frontend Design

The frontend is built using:

* HTML
* CSS
* JavaScript

### Components:

* Home Page
* Login/Register Page
* Event Listing Page
* Booking Page

### Files:

* htmlPages/
* static/
* mystaticFiles/
* media/

---

## 3. Backend Design

The backend is implemented using Django framework.

### Main Modules:

* Administrator
* Coordinator
* EventHead
* EventWebSite
* UserManager

### Responsibilities:

* Handle user requests
* Process business logic
* Manage authentication
* Interact with database

---

## 4. Database Design

Database used: **SQLite**

Main tables include:

* Users
* Events
* Bookings

The database is managed using Django ORM, which automatically handles table creation and relationships.

---

## 5. System Flow

1. User accesses website
2. User logs in or registers
3. User views available events
4. User books or participates in event
5. Data stored in database

---

## 6. Data Flow Diagram (Textual)

User → Frontend → Backend → Database → Backend → Frontend → User

---

## 7. Security Design

* User authentication using Django
* Role-based access control
* Input validation

---

## 8. Scalability

* Modular Django apps allow easy expansion
* New features can be added without affecting existing modules

---

## 9. Conclusion

The system is designed to be modular, scalable, and easy to use. It efficiently manages event-related activities while ensuring data integrity and security.
