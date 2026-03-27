# Password-Complexity-Checker


🔐 Password Complexity Checker in Python

📌 Overview

This project implements a Password Complexity Checker using Python. It evaluates the strength of a password based on multiple security criteria such as length, uppercase letters, lowercase letters, digits, and special characters.

🎯 Objective

To develop a Python program that:

- Analyzes password strength
  
- Classifies it as Weak, Medium, or Strong
  
- Provides suggestions to improve weak passwords

🛠️ Technologies Used

- Python 3
  
- No external libraries required

⚙️ How It Works

1. The user enters a password.
   
2. The program checks:
   - Minimum length (≥ 8 characters)
   - Presence of uppercase letters (A–Z)
   - Presence of lowercase letters (a–z)
   - Presence of digits (0–9)
   - Presence of special characters (!@#$%^&*)
     
3. Each condition contributes to a score.
   
4. Based on the score, the password is classified:
   - 0–2 → Weak
   - 3–4 → Medium
   - 5 → Strong
     
5. Suggestions are provided for missing criteria.

🔑 Example

Input:

Password: hello

Output:

Suggestion: Password should be at least 8 characters

Suggestion: Add at least one uppercase letter

Suggestion: Add at least one number

Suggestion: Add at least one special character

Password Strength: Weak


🚀 Features

- Checks multiple password security rules
  
- Provides real-time suggestions
  
- Classifies password strength
- Beginner-friendly implementation

📚 Learning Outcomes

- Understanding password security principles
  
- Working with strings and conditions in Python

- Implementing validation logic
  
- Improving cybersecurity awareness

📝 Conclusion

This project demonstrates how password strength can be evaluated using simple programming logic. It helps users create more secure passwords and understand the importance of strong authentication practices.
