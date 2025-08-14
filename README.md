# Password_strength_Evaluation

##  Overview
This task focused on understanding what makes a password strong, testing different passwords with varying complexity levels, and identifying best practices for secure password creation.

---

## 🛠 Tools Used
- Online password strength checkers:
  - https://passwordmeter.com
  - https://www.passwordmonster.com
  - https://password.kaspersky.com
- OS: Linux (Kali) / Windows

---

## 📋 Steps Performed
1. Created **5 passwords** with different complexities (weak, medium, strong, passphrase).
2. Tested each password in online strength checkers.
3. Recorded:
   - Strength rating
   - Estimated crack time
   - Security feedback
4. Researched common password attacks.
5. Summarized best practices for creating strong passwords.

---

## 🔍 Example Results
| Password Example | Complexity | Strength | Crack Time | Feedback |
|------------------|------------|----------|------------|----------|
| `password`       | Weak       | Very Weak| < 1 sec    | Too short, only lowercase |
| `password123`    | Weak       | Weak     | Seconds    | Contains dictionary word |
| `Pass1234`       | Medium     | Weak     | Hours      | Needs symbols, longer length |
| `P@ssw0rd2025!`  | Strong     | Strong   | Centuries  | Good complexity, length |
| `Blue_Tiger_Jumps_Over_3_Mountains!`     | Very Strong | Excellent | Millions of years | Long passphrase, high entropy |

---

## 🧠 Learning Outcomes
- Password length significantly increases crack time.
- Mixing uppercase, lowercase, numbers, and symbols makes brute force harder.
- Passphrases are easier to remember and highly secure.
- Dictionary words reduce strength drastically.

---

## 📜 License
MIT License
