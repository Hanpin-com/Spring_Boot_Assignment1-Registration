# Course Registration Spring Boot Application

## Description
Develop a basic Spring Boot web application using Spring MVC and Thymeleaf to allow users to
submit a registration form for a course. The data should be displayed on a confirmation page
after form submission.

---

## Feature
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