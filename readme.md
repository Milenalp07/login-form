# Student Login Form

This project is a simple **Student Login Form** built using **HTML, CSS, and JavaScript**.  
It demonstrates form validation, error handling, and basic user interaction using JavaScript.

The project was created as part of a JavaScript practice assignment.

---

## Features

The web page includes a styled login form with the following fields:

- First Name
- Last Name
- Email
- Password
- Student ID

### Form behaviour

- The form **prevents submission** if any field fails validation.
- A **specific error message** appears below each invalid field.
- Error messages are **hidden when the field becomes valid**.
- When the form is successfully submitted:
  - All input fields are **cleared**
  - All error messages are **hidden**
  - The login form is **hidden**
  - A **success message** is displayed.

---

## Technologies Used

- **HTML5** – page structure  
- **CSS3** – styling and layout  
- **JavaScript (Vanilla JS)** – form validation and interaction  

No external libraries or frameworks were used.

---

## Project Structure


login-form
│
├── index.html
└── README.md


All HTML, CSS, and JavaScript code is included in the **index.html** file.


## Form Validation Rules

| Field | Validation |
|-----|-----|
| First Name | Cannot be empty |
| Last Name | Cannot be empty |
| Email | Must be a valid email format |
| Password | Minimum 6 characters |
| Student ID | Cannot be empty |

---

## Author

Student: Milena Pires  
Student ID: 75632