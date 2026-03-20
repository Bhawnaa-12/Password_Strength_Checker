# Password Strength Checker 🔐

## Overview

This Python program checks the strength of a password based on several security criteria such as length and character diversity. It also provides helpful suggestions to improve weak passwords.

## Features

* Evaluates password strength as **Weak**, **Medium**, or **Strong**
* Checks for:

  * Minimum length (8 characters)
  * Uppercase letters
  * Lowercase letters
  * Numbers (digits)
  * Special characters
* Gives actionable suggestions to improve password security

## Requirements

* Python 3.x

## How It Works

The program uses regular expressions to analyze the password and assigns a score based on the following criteria:

* +1 if password length ≥ 8
* +1 if it contains uppercase letters
* +1 if it contains lowercase letters
* +1 if it contains digits
* +1 if it contains special characters

### Strength Levels

* **Weak ❌**: Score ≤ 2
* **Medium ⚠️**: Score = 3 or 4
* **Strong ✅**: Score = 5

## Usage

1. Run the script:

   ```bash
   python password_checker.py
   ```
2. Enter your password when prompted.
3. View the strength rating and suggestions (if any).

## Example

```
Enter your password: Pass123

Password Strength: Medium ⚠️
Suggestions to improve:
- Add special characters
```

## Suggestions Provided

If the password does not meet certain criteria, the program suggests improvements such as:

* Use at least 8 characters
* Add uppercase letters
* Add lowercase letters
* Include numbers
* Add special characters

## File Structure

```
password_checker.py
README.md
```

## Future Improvements

* Add GUI interface
* Integrate password breach checking
* Provide real-time feedback while typing

## License

This project is open-source and free to use.
