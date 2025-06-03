# Password Strength Evaluation Report
This project explores how to create and evaluate strong passwords using [PasswordMeter.com](https://www.passwordmeter.com) and summarizes the key lessons learned from the process.

---

## Objective
- Understand what makes a password strong
- Create passwords with varying complexity
- Evaluate each password using a strength checker
- Identify best practices for secure password creation
- Study common password attacks and how complexity protects against them

---

## Password Evaluation Results

| No. | Password           | Description                                 | Score | Strength     |
|-----|--------------------|---------------------------------------------|-------|--------------|
| 1️1.| `suraj123`         | Lowercase + numbers                         | 39%   | Weak         |
| 2️2.| `surajkish`        | Lowercase only                              | 10%   | Weak         |
| 3️3.| `SURAJKISH`        | Uppercase only                              | 30%   | Weak         |
| 4️4.| `Suraj123`         | Mixed case + numbers                        | 58%   | Moderate     |
| 5️5.| `Suraj@123`        | Mixed case + numbers + symbol               | 78%   | Strong       |
| 6️6.| `$ur@j!2025`       | Lowercase + numbers + symbols               | 75%   | Strong       |
| 7️7.| `$Ur@j!2025`       | Mixed case + symbols + numbers              | 88%   | Very Strong  |
| 8️8.| `&zM!9hK@uL3*BfQw` | Full random combo with high entropy         | 98%   | Very Strong  |

---

## Best Practices for Creating Strong Passwords

1. Use a mix of uppercase, lowercase, numbers, and symbols  
2. Ensure a minimum length of 12–16 characters  
3. Avoid names, dictionary words, or predictable patterns  
4. Add randomness and special characters  
5. Do not reuse passwords across accounts  
6. Use a password manager for secure storage  
7. Enable two-factor authentication (2FA) for critical accounts

---

## Tips Learned from the Evaluation

- Lowercase-only and uppercase-only passwords are very weak  
- Mixing cases and adding numbers improves strength  
- Including at least one symbol significantly boosts the score  
- Random and long passwords (16+ characters) are extremely strong  
- Avoiding personal information and common patterns is critical

---

## Common Password Attacks

| Attack Type        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| "Brute Force"     | Attempts every possible combination; slow but effective on weak passwords  |
| "Dictionary"      | Uses known/common words to guess passwords                                 |
| "Credential Stuffing"| Tries breached credentials on multiple sites                          |
| "Hybrid"          | Mix of dictionary and brute force (e.g., “Password123”)                    |
| "Phishing"        | Tricks users into revealing their password via fake pages or emails        |

---

##  How Password Complexity Affects Security

- More character variety increases resistance to attacks  
- Longer passwords dramatically raise the difficulty of brute force attacks  
- Random placement of characters prevents dictionary pattern recognition  
- Avoiding common words, sequences, and reused passwords is essential

---
