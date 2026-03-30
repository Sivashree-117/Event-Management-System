#  Requirements Document – Event Management System

## 1. Introduction

The Event Management System is a web-based application developed using Django. It allows users to view, manage, and participate in events. The system supports multiple roles such as Administrator, Coordinator, Event Head, and Users.

---

## 2. Functional Requirements

### 2.1 User Management

* Users can register and login into the system
* Role-based access (Admin, Coordinator, Event Head, User)
* Users can update their profile

### 2.2 Event Management

* Create new events
* Update event details
* Delete events
* View list of available events

### 2.3 Booking/Participation

* Users can register for events
* View registered events
* Manage participation

### 2.4 Admin Features

* Manage all users
* Manage events
* Monitor system activities

---

## 3. Non-Functional Requirements

### 3.1 Performance

* System should load pages within 2–3 seconds

### 3.2 Usability

* User-friendly interface
* Easy navigation

### 3.3 Security

* Authentication and authorization
* Secure login system

### 3.4 Reliability

* System should handle multiple users without crashing

---

## 4. Hardware Requirements

* Minimum 4GB RAM
* Standard computer system

---

## 5. Software Requirements

* Python 3.x
* Django Framework
* SQLite Database
* Web Browser (Chrome/Edge)

---

## 6. Assumptions

* Users have internet access
* Basic knowledge of web usage

---

## 7. Constraints

* Limited to web-based access
* Uses SQLite for simplicity
