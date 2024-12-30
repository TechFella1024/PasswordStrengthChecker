# Password Strength Checker

## Overview
This project is a Python script that evaluates the strength of a password based on length, complexity, and common patterns. It categorizes passwords as **Strong**, **Medium**, or **Weak**.

## Features
- Validates passwords against the following criteria:
  - At least 12 characters in length.
  - Contains both uppercase and lowercase letters.
  - Includes numbers and special characters.
  - Avoids common weak patterns (e.g., `123456`, `password`, `qwerty`).

## Tools Used
- **Python 3**
- **Regular Expressions (`re` module)**

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Password-Strength-Checker.git
   cd Password-Strength-Checker
   ```

2. Run the script:
   ```bash
   python3 password_checker.py
   ```

3. Enter a password when prompted, and view the output (e.g., Strong, Medium, Weak).

---

## Screenshots
Below is the list of screenshots included in this project:

1. **Script Running in Action**:
   - Shows the Python script prompting for a password and displaying the result.  
   - Filename: `script_terminal_example.png`

2. **Weak Password Output**:
   - Output when entering a weak password (e.g., `password123`).  
   - Filename: `weak_password.png`

3. **Medium Password Output**:
   - Output when entering a medium-strength password (e.g., `Password123`).  
   - Filename: `medium_password.png`

4. **Strong Password Output**:
   - Output when entering a strong password (e.g., `Str0ngP@ssw0rd!`).  
   - Filename: `strong_password.png`

---

## Example Outputs
Below are examples of outputs based on different password strengths:

1. **Weak Password**:  
   - Password: `password123`  
   - Strength: Weak  
   ![Weak Password Example](screenshots/weak_password.png)

2. **Medium Password**:  
   - Password: `Password123`  
   - Strength: Medium  
   ![Medium Password Example](screenshots/medium_password.png)

3. **Strong Password**:  
   - Password: `Str0ngP@ssw0rd!`  
   - Strength: Strong  
   ![Strong Password Example](screenshots/strong_password.png)

---

## Lessons Learned
- **Password Complexity**: Understanding how common patterns affect password strength.
- **Python Programming**: Gained hands-on experience with string analysis and regular expressions.
- **Project Documentation**: Learned to structure a GitHub project with clear explanations and visuals.

---

## Next Steps
- Add a graphical user interface (GUI) for non-terminal users.
- Implement functionality to check passwords against a larger dictionary of common weak passwords.

---

## Acknowledgments
- Inspired by cybersecurity best practices and password management techniques.
