# Student-Enrollment-Form
JSON Power DB
Here’s a sample `README.md` for a Student Enrollment Form project:

---

# Student Enrollment Form

## Overview

The Student Enrollment Form is a web application that allows users to manage student records. The form enables users to enter new student information or update existing records based on a unique Student ID. The application interacts with a backend database to store and retrieve student data.

## Features

- **Add New Student**: Allows users to enter details for a new student if the Student ID does not already exist.
- **Update Existing Student**: Enables users to update the information of an existing student using their Student ID.
- **Reset Form**: Clears the form fields and disables the Save and Change buttons.
- **Form Validation**: Ensures all fields are filled before saving or updating data.

## Technologies Used

- **HTML**: Structure and layout of the form.
- **JavaScript**: Form validation, data handling, and AJAX requests.
- **Bootstrap**: Styling and responsive design.
- **jQuery**: Simplifies DOM manipulation and AJAX requests.
- **JSON-PDB**: Database interaction for CRUD operations.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd student-enrollment-form
   ```

2. **Open `index.html`**: Open the `index.html` file in a web browser to view and interact with the form.

## Usage

1. **Load the Form**: The form will be displayed with three buttons: Save, Change, and Reset. By default, the Save and Change buttons are disabled.

2. **Add New Student**:
   - Enter a unique Student ID.
   - If the Student ID does not exist, the Save and Reset buttons will be enabled.
   - Fill out all required fields (Name, Salary, HRA, DA, Deduction).
   - Click the Save button to add the new student.

3. **Update Existing Student**:
   - Enter an existing Student ID.
   - If the Student ID exists, the Change and Reset buttons will be enabled.
   - Modify the necessary fields.
   - Click the Change button to update the student's information.

4. **Reset Form**:
   - Click the Reset button to clear all fields and reset the form to its initial state.

## File Structure

- **index.html**: Main HTML file containing the form and associated scripts.
- **lockdown-install.js**: JavaScript file used for lockdown installation (if applicable).

## Dependencies

- **Bootstrap**: For styling and responsive design.
- **jQuery**: For DOM manipulation and AJAX.
- **JSON-PDB**: For backend database interaction.

## Troubleshooting

- **Change Button Not Enabling**: Ensure that the correct Student ID is entered and exists in the database.
- **Form Validation Errors**: Ensure all required fields are filled out before saving or updating.

## Contributing

Contributions are welcome! Please submit a pull request or raise an issue for any bugs or enhancements.

## License

This project is licensed under the MIT License.

----
