# Task 6 – Strong Password Creation and Evaluation

## Objective
To understand what makes a password strong by creating various types of passwords and evaluating them using free online password strength checkers.

## Passwords Tested

| Password               | Strength (%) | Score        | Feedback                                |
|------------------------|--------------|--------------|-----------------------------------------|
| `password123`          | 22%          | Weak         | Common pattern, lacks complexity        |
| `Password123`          | 41%          | Fair         | Better, but missing special characters  |
| `Pass@123`             | 65%          | Good         | Includes symbol and numbers             |
| `!P@ssW0rd#2025!`      | 95%          | Strong       | Very complex and long                   |
| `Sun$et@Beach2025Happy!`| 100%        | Very Strong  | Excellent passphrase: long + complex    |

Tested on: [https://passwordmeter.com](https://passwordmeter.com)

## Key Learnings

- **Password Length**: Longer passwords are harder to crack.
- **Character Variety**: Mixing **uppercase, lowercase, numbers, and symbols** significantly improves password strength.
- **Passphrases**: A long sentence-style password (e.g., `Sun$et@Beach2025Happy!`) is easy to remember yet very secure.
- **Avoid Predictable Patterns**: Avoid using dictionary words, birth dates, or sequences like `12345`, `qwerty`.
- **Best Practice**: Use a **unique** password for each platform and **enable multi-factor authentication (MFA)** for additional protection.


## Research – Common Password Attacks

### 1. Brute Force Attack
- The attacker tries **every possible combination** of characters until the correct password is found.
- The more complex and longer your password is, the longer it takes to crack.

### 2. Dictionary Attack
- A list of **common passwords or words** is used to guess the password.
- Passwords like `iloveyou`, `admin`, `letmein`, and `password123` are commonly tried in this method.

### 3. Hybrid Attack
- Combines a **dictionary attack with brute force**, adding variations like `password123`, `Password@2023`.

### 4. Credential Stuffing
- Attackers use **leaked username-password combos** from data breaches and try them on other sites.

###  5. Rainbow Table Attack
- Precomputed hashes are used to reverse-engineer stored password hashes.
- Can be defended against using **salting and strong hashing algorithms**.

## Bonus: What Is MFA?
**Multi-Factor Authentication (MFA)** adds a second layer of security — e.g., password + OTP/email code/biometric. Even if your password is leaked, MFA protects your account.

## Tools Used
- [https://passwordmeter.com](https://passwordmeter.com) – Password Strength Evaluator

## Screenshots
(Save and upload screenshots of the password strength results here)

## Author
**Name**: Purushothaman K  
**Internship Task**: Cybersecurity – Task 6  
**Date**: June 2025  
