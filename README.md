# User Login UI

This is a simple **User Login UI** built with **HTML** and **JavaScript**. It features a basic login form with client-side validation for username and password fields. The validation ensures that both fields are filled before the login attempt is made.

## Features

- Basic login form with username and password input fields.
- Client-side validation to ensure both username and password fields are not empty.
- Displays feedback to the user based on the credentials provided (success or error messages).
- No CSS is used, only HTML and JavaScript for simplicity.
- Checks user credentials against a predefined list of valid users.

## Files

- `index.html`: Contains the HTML structure and embedded JavaScript for the login form, validation, and feedback.

## Usage

1. **Download the project**:
   - Copy the code or download the `index.html` file to your local machine.

2. **Open the project**:
   - Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Edge).

3. **Functionality**:
   - Enter a username and password in the respective fields and click the **Login** button.
   - If both fields are empty, an error message will prompt the user to fill in the required fields.
   - If the credentials match a predefined list, the user will see a "Logging in Successfully" message. Otherwise, an "Invalid credentials" message will be shown.

4. **Users**:
   - Predefined users: "User1", "User2", "User3", "User4".
   - Corresponding passwords: "qwerty", "Ish1", "nonewar", "run1".

## Technologies Used

- **HTML**: For structuring the login page and the form.
- **JavaScript**: For client-side validation and credential checking.

## How to Modify or Extend

- **Backend Integration**: The project is static and does not interact with a server. You can modify the JavaScript code to send the login data to a backend for real authentication.
- **Extend Validation**: You can add more complex validation logic, such as regex validation for username or password strength.
- **Styling**: Since no CSS is used, feel free to add a custom stylesheet to enhance the look and feel of the login page.
