# Day 10 - REACT ASSIGNMENT

## Registration Form using React Hook Form and Zod Schema Validation

This project implements a registration form for a website using React Hook Form for form state management and validation, and Zod schema validation for custom error messages. The form includes fields for username, email address, password, confirm password, and an optional phone number.

## Features Implemented

- **Form Setup:** Utilized `useForm` hook from React Hook Form for managing form state and validation.
- **Field Validation:**
  - Username: Required field with a minimum length of 3 characters.
  - Email Address: Required field with valid email format validation.
  - Password: Required field with a minimum length of 8 characters, including at least one uppercase letter, one lowercase letter, one number, and one special character.
  - Confirm Password: Required field that must match the password field.
  - Phone Number: Optional field with a valid phone number format if provided.
- **Custom Error Messages:** Implemented custom error messages for each validation rule using Zod schema validation.
- **Form Submission:** Implemented form submission using the `handleSubmit` method and displayed a success message upon successful submission.
- **Reset Button:** Included a "Reset" button that clears all fields and error messages when clicked.
- **Password Match Check:** Used the `watch` method to track changes in the password and confirm password fields and displayed a message if they do not match.
- **Display Phone Number:** Displayed the current value of the phone number field below the form using the `watch` method.

## Extra

- **Password Complexity:** Implementing the password validation with multiple requirements (uppercase, lowercase, numbers, special characters) was challenging to ensure all conditions were met.
- **Custom Error Messages:** Defining and displaying custom error messages for each validation rule required careful handling to ensure clarity and consistency.
