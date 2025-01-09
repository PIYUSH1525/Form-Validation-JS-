# Form Validation in JavaScript

This project demonstrates a **Sign-Up Form** with validation features implemented using JavaScript, HTML, and Bootstrap 4. The form validates user inputs in real-time and ensures that the data is properly formatted before submission.

## Features

- **Responsive Design**: Styled with Bootstrap 4 for a clean and user-friendly interface.
- **Real-Time Validation**: JavaScript functions validate user inputs such as:
  - Name: Non-empty input.
  - Email: Proper email format.
  - Username: Non-empty and valid characters.
  - Password: Non-empty and matching confirmation.
  - Mobile Number: Proper numeric format.
- **Dynamic Error Display**: Error messages appear in red beside invalid fields.
- **Interactive Controls**:
  - "Submit" button validates the form and processes the input.
  - "Reset" button clears all fields.
  - Navigation link to login page for existing users.

## Prerequisites

- **Technologies Used**:
  - HTML for structure.
  - Bootstrap for styling.
  - JavaScript for validation logic.
- **Required Libraries**:
  - [Bootstrap 4](https://getbootstrap.com/docs/4.0/)
  - [jQuery](https://jquery.com/)
  - [Popper.js](https://popper.js.org/)

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/form-validation-js.git
   cd form-validation-js
   ```
2. Open the `index.html` file in your browser.
3. Fill in the form fields and test the validation features.

## File Structure

- `index.html`: Contains the HTML structure of the form.
- `scripts/signup.js`: JavaScript file for form validation logic.
- `styles`: Optional folder for custom CSS (not included in the base version).

## Example Validation Rules

- Name: Cannot be empty.
- Email: Must follow the standard email format (e.g., user@example.com).
- Password: Must match the confirmation password.
- Mobile Number: Must contain only numbers.

## Screenshots

![Sign-Up Form](https://via.placeholder.com/800x400.png?text=Form+Validation+Demo)


