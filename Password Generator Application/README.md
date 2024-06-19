# Password Generator Application

[![powered by](https://img.shields.io/badge/Powered%20by-Python%203-blue)](https://www.python.org/)

## Overview
This Python application generates strong and random passwords based on user-defined parameters such as length and complexity. It provides a user-friendly interface for creating secure passwords for various online accounts.

## Technologies Used
- **Python:** The core programming language used to build the application.
- **Random Module:** Used to generate random characters for the password.
- **String Module:** Utilized for accessing different sets of characters (e.g., letters, digits, punctuation) to construct passwords.

## How It Works
**1.  User Input**
- The application prompts the user to specify the desired length and complexity of the password.

**2.  Generate Password**
- Depending on the user's specified complexity level, the application selects an appropriate set of characters (e.g., lowercase letters, digits, punctuation) to use in generating the password.

**3.  Creating the Password**
- The application uses a combination of random characters from the selected character set to generate a password of the specified length.

**4.  Display the Password**
- The generated password is then displayed on the screen for the user to use.

## Complexity Levels
**1.  Low Complexity**
- Uses lowercase letters and digits.

**2.  Medium Complexity**
- Includes lowercase letters, digits, and punctuation.

**3.  High Complexity**
- Utilizes lowercase letters, uppercase letters, digits, and punctuation.

## How to Use
1. Run the **[passwordgenerator.py](passwordgenerator.py)** script using Python.
2. Follow the prompts to specify the desired length and complexity of the password.
3. The generated password will be displayed on the screen.

## Example Usage
```mathematica
Welcome to the Password Generator!

Enter the desired length of the password: 37
Enter the complexity (low, medium, high): high

Generated Password: bW!tL-G;}jSM8u^C+I~JJ^Ap@S:wHLa*Y}I4/
```