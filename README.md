🐾 Contact Form with HTML Validation (Pet Care)

📌 Project Overview

This project is a creative contact form designed for a Pet Care website using HTML and CSS only.
The main focus of this task is to demonstrate HTML5 form validation without using JavaScript.

The form collects basic user information and relies on the browser’s built-in validation mechanism.

🎯 Objectives

Create a user-friendly contact form

Apply proper input types

Use HTML5 validation attributes

Ensure accessibility using labels

Style the form creatively using CSS

Understand default browser validation behavior

📄 Form Fields

The contact form includes the following fields:

Owner Name (Text)

Email Address (Email)

Phone Number (Telephone with pattern)

Pet Type (Text)

Message (Textarea)

All fields are mandatory.

🛠 Technologies Used

HTML5

<form>, <input>, <textarea>, <button>

Validation attributes: required, pattern, maxlength

CSS3

Layout styling

Colors, spacing, and responsiveness

❌ No JavaScript (as required)

📁 Project Structure
Contact-Form/
│── contact-form.html
│── form-style.css
│── README.md

✅ HTML Validation Used
Attribute	Purpose
required	Prevents empty submission
type="email"	Validates email format
type="tel"	Accepts phone input
pattern	Enforces phone number format
maxlength	Limits text length

The browser automatically displays validation error messages.

🧪 Validation Behavior

Empty fields → Browser shows “Please fill out this field”

Invalid email → Browser asks for correct email format

Incorrect phone format → Pattern mismatch error

Message exceeds character limit → Input blocked

▶ How to Run

Open the project folder

Open contact-form.html in any web browser

Try submitting the form with empty or incorrect values to test validation

📌 Data Handling

The form does not store or send data

It is designed only to demonstrate HTML validation

Backend integration is outside the scope of this task
