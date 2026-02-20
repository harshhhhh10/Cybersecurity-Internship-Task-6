 Task 6 – Create a Strong Password and Evaluate Its Strength

  Objective
Understand what makes a password strong, and test multiple passwords against a real password-strength tool (passwordmeter.com).



  Tool Used
- Website: [passwordmeter.com](https://passwordmeter.com)
- Type: Free online password strength checker
- Metrics Provided: Score (%), Complexity rating, Additions & Deductions breakdown



  Passwords Tested & Results

|  | Password | Score | Complexity | Key Observation |
||-|-||--|
| 1 | `password` | 8% | Very Weak | Only lowercase letters, common dictionary word, no symbols or numbers |
| 2 | `pass@123` | 57% | Good | Has symbol and numbers but no uppercase, short length |
| 3 | `P@ssw0rd!2026` | 100% | Very Strong | Mix of all character types, 13 characters long |
| 4 | `T9kL$mQzI2vXw@` | 100% | Very Strong | 15 characters, random mix, no patterns, best result |



  Screenshots

 1. Very Weak Password – `password` (Score: 8%)
📁 Screenshot: `screenshots/01_very_weak_password.png`
- ❌ No uppercase letters
- ❌ No numbers
- ❌ No symbols
- ❌ Common dictionary word
- Deduction: Letters only, consecutive lowercase letters



 2. Medium Password – `pass@123` (Score: 57%)
📁 Screenshot: `screenshots/02_medium_password.png`
- ✅ Has symbol (@)
- ✅ Has numbers (123)
- ❌ No uppercase letters
- ❌ Short length (8 chars)
- Deduction: Consecutive lowercase letters, sequential numbers



 3. Strong Password – `P@ssw0rd!2026` (Score: 100%)
📁 Screenshot: `screenshots/03_strong_password.png`
- ✅ Uppercase letter (P)
- ✅ Symbols (@, !)
- ✅ Numbers (0, 2026)
- ✅ 13 characters long
- ✅ Meets all minimum requirements



 4. Very Strong Password – `T9kL$mQzI2vXw@` (Score: 100%)
📁 Screenshot: `screenshots/04_very_strong_password.png`
- ✅ 15 characters
- ✅ 4 uppercase letters
- ✅ 4 symbols (, $, @)
- ✅ No sequential or repeated characters
- ✅ Completely random — hardest to crack



  Analysis – How Complexity Affects Security

As seen from the tests, each improvement in password complexity dramatically increases its strength:

- Going from letters only (8%) to adding symbols + numbers jumped the score to 57%
- Adding uppercase + more length pushed it to 100%
- Using a fully random 15-character password with no patterns achieved a perfect score with zero deductions

The key insight is that length + randomness + character variety together make a password exponentially harder to crack.



  Best Practices for Strong Passwords

1. Use at least 12–16 characters — longer is always better
2. Mix all 4 character types — uppercase, lowercase, numbers, symbols
3. Avoid dictionary words — even with letter substitutions (e.g., `p@ssword` is still weak)
4. No personal info — avoid names, birthdays, phone numbers
5. No sequential patterns — avoid `123`, `abc`, `qwerty.`
6. Use a unique password for every account
7. Use a password manager to generate and store complex passwords
8. Consider passphrases — e.g., `Sun!MangoRiver9Tree` — long, memorable, strong



  Common Password Attacks

 1. Brute Force Attack
The attacker tries every possible combination of characters until the correct password is found. Longer and more complex passwords make this computationally infeasible — a 15-character random password could take centuries to brute force.

 2. Dictionary Attack
The attacker uses a precompiled list of common words, phrases, and known passwords (like `password`, `123456`, `admin`). This is why using real words — even with simple substitutions — is dangerous.

 3. Credential Stuffing
Attackers take leaked username/password pairs from data breaches and try them on other websites. This is why reusing passwords across sites is extremely risky.

 4. Rainbow Table Attack
Precomputed tables of password hashes are used to reverse-engineer passwords. Strong, unique passwords combined with proper hashing (salting) defeat this.



 Interview Questions & Answers

1. What makes a password strong?
A combination of length (12+ characters), uppercase and lowercase letters, numbers, and symbols, with no dictionary words or personal information.

2. What are common password attacks?
Brute force, dictionary attacks, credential stuffing, phishing, and rainbow table attacks.

3. Why is password length important?
Every additional character multiplies the number of possible combinations exponentially. A 15-character password has trillions more possibilities than an 8-character one.

4. What is a dictionary attack?
An attack in which the hacker tries passwords from a list of common words and known passwords rather than guessing randomly.

5. What is multi-factor authentication (MFA)?
MFA requires a second form of verification beyond just a password — such as a one-time code sent to your phone, a fingerprint, or an authenticator app. Even if your password is stolen, MFA blocks unauthorized access.

6. How do password managers help?
They generate long, random, unique passwords for every site and store them securely. You only need to remember one master password.

7. What are passphrases?
Passphrases are long passwords made from a sequence of random words, e.g., `Blue!TigerRain9Cloud`. They are easier to remember than random characters, but very hard to crack due to their length.

8. What are common mistakes in password creation?
- Using simple words like `password` or `123456`
- Using personal info (name, birthday)
- Reusing the same password across multiple accounts
- Using short passwords (under 8 characters)
- Making predictable substitutions like `@` for `a`



  Repository Structure


Cybersecurity-Internship-Task-6/
├── README.md
└── screenshots/
    ├── 01_very_weak_password.png
    ├── 02_medium_password.png
    ├── 03_strong_password.png
    └── 04_very_strong_password.png




  Conclusion

This task clearly demonstrated how password complexity directly impacts security. A simple dictionary word scored only 8%, while a random 15-character password with mixed character types scored 100%. The most important takeaways are: use long, random, unique passwords and enable MFA wherever possible.


