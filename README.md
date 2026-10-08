# Registration Form

A simple, client-side registration form built with HTML, Tailwind CSS utility
classes, and JavaScript. It provides a centered form for entering a name, email
address, and password, with inline validation feedback.

## Features

- Name, email, and password fields.
- Inline validation while typing:
  - Name and email must not be empty.
  - Email must match a basic email address pattern.
  - Password must be at least 6 characters long.
- The **Sign Up** button appears only when all fields pass validation.
- Styled with Tailwind CSS, the Arimo font, and Font Awesome.

## Getting Started

No build tools or package installation are required.

1. Open `registrerform.html` directly in a web browser.
2. Enter a name, a valid email address, and a password of at least 6 characters.
3. Once the inputs are valid, the **Sign Up** button will appear.

The page loads Tailwind CSS, Google Fonts, and Font Awesome from CDNs, so an
internet connection is needed for those external styles and icons.

## Project Structure

```text
Registrationform/
├── README.md
└── registrerform.html
```

## Note

This is a front-end demonstration. The **Sign Up** button is shown when the
inputs are valid, but there is no form submission handler, account creation,
or server-side validation.
