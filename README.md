# Password Strength Checker

A simple web-based application that checks the strength of a user's password input in real-time. The password is evaluated as either **weak**, **medium**, or **strong**, based on its length, and the corresponding visual feedback is given.

## Features

- **Real-time Feedback**: As you type your password, it immediately gives feedback on whether the password is weak, medium, or strong.
- **Color Indicators**: The strength of the password is visually represented by color:
  - Weak: Red
  - Medium: Yellow
  - Strong: Green

## Project Structure

```bash
│
├── index.html        # The main HTML file for the password input and feedback display
├── style.css         # The CSS file for styling the input box and message
└── script.js         # The JavaScript file responsible for checking password strength and updating the display
