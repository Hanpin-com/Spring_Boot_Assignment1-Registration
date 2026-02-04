# Course Registration Spring Boot Application

## Description
A simple Spring Boot web application using Spring MVC and Thymeleaf.  
Students can fill out a course registration form and view their submitted information on a confirmation page.

This project is created for **Assignment 1: Spring Boot Web Application with Forms**.

---

## Features
- Registration form (name, email, course, level of study)
- Confirmation page displaying submitted data
- Thymeleaf templates
- Basic CSS styling
- No database required

---

## Project Structure
```
registration
├── ScreenShot
│ ├── Register Page.png
│ ├── Register Page (input data).png
│ └── Confirmation Page.png
└── src
└── main
├── java
│ └── com.example.registration
│ ├── RegistrationApplication.java
│ ├── controller
│ │ └── RegistrationController.java
│ └── model
│   └── Student.java
└── resources
├── templates
│ ├── register.html
│ └── confirmation.html
└── static
  └── style.css
```

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/Hanpin-com/Spring_Boot_Assignment1-Registration.git
Open the project in IntelliJ IDEA (or Eclipse).

Run:

RegistrationApplication.java
Open a browser and go to:

http://localhost:8080/register
```
Screenshots
Register Page

1. ScreenShot/Register Page.png
2. ScreenShot/Register Page (input data).png

Confirmation Page

1. ScreenShot/Confirmation Page.png