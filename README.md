# 🔐 Task 6: Password Strength Evaluation

## 🎯 Objective
To understand the components of a strong password by testing various examples using an online strength checker and summarizing best practices, common threats, and the role of complexity in password security.

---

## 🧪 Passwords Tested & Results

| Password                  | Strength Score | Complexity    | Comments                                              |
|---------------------------|----------------|----------------|-------------------------------------------------------|
| `123456`                  | 4%             | Very Weak      | Common numeric password, short and predictable.       |
| `password1`               | 26%            | Weak           | Dictionary word + digit. Low complexity.              |
| `Pa$$w0rd2025`            | 100%           | Very Strong    | Good use of symbols and numbers, moderate strength.   |
| `Tm3T0L3@rn#CS`           | 100%           | Very Strong    | Strong complexity with mixed characters.              |
| `C0mpl3x#CyberS3cur1ty!`  | 100%           | Very Strong    | Long and complex, highly resistant to attacks.        |

---

## ✅ Best Practices for Creating Strong Passwords

1. Use **12+ characters** at minimum.
2. Include **uppercase**, **lowercase**, **numbers**, and **symbols**.
3. Avoid using common words, names, or predictable patterns.
4. Use **random combinations** or **passphrases** (e.g., `MyC@tEats2Much!`).
5. Never reuse passwords across websites.

---

## ✍️ Tips Learned from the Evaluation

- **Longer passwords** with more variation in character type score much higher.
- Including **symbols and digits** significantly increases strength.
- Passwords that avoid **sequential or repeated characters** perform better.
- Even one missing category (e.g., no symbols) drops the score drastically.
- Complexity directly correlates to the time required to crack the password.

---

## 🧨 Common Password Attacks

| Attack Type           | Description |
|-----------------------|-------------|
| **Brute Force Attack** | Attempts every possible combination. Long, complex passwords resist this best. |
| **Dictionary Attack**  | Tries words from a precompiled list. Common passwords like `password123` are easy to crack. |
| **Credential Stuffing**| Uses leaked credentials from one site on another. Password reuse increases this risk. |
| **Phishing**           | Tricks users into revealing credentials. Social engineering technique. |

---

## 🔎 Why Password Complexity Matters

- A complex password (long, mixed character types) increases **entropy** — the measure of unpredictability.
- Complexity exponentially increases the **time and effort** required for brute force.
- Simple passwords (like `123456` or `qwerty`) can be cracked **instantly**.
- A strong password provides a **first line of defense** against intrusion.

---

## 🔐 What Are Passphrases?

- Passphrases are sequences of **random or meaningful words** (e.g., `CorrectHorseBatteryStaple!`).
- Easier to remember than random strings, but just as secure — especially when combined with **numbers and symbols**.

---

## 🔑 How Password Managers Help

- Generate and store **unique, strong passwords** for every account.
- Prevent password reuse across websites.
- Offer **secure autofill** and **encryption** for stored credentials.

---

## 🛠️ Tools Used

- 🔍 [PasswordMeter.com](https://www.passwordmeter.com) — for testing password strength and getting feedback.

---

## 📸 Screenshots

All strength evaluation screenshots are in the [`Screenshots/`](./Screenshots) folder:

- [password_test1.png](./Screenshots/password_test1.png) — `123456`
- [password_test2.png](./Screenshots/password_test2.png) — `password1`
- [password_test3.png](./Screenshots/password_test3.png) — `Pa$$w0rd2025`
- [password_test4.png](./Screenshots/password_test4.png) — `Tm3T0L3@rn#CS`
- [password_test5.png](./Screenshots/password_test5.png) — `C0mpl3x#CyberS3cur1ty!`

---

## 📌 Conclusion

This task showed that **length + complexity = strength**. Simple passwords are not just unsafe — they're dangerous. The most effective protection comes from:
- Strong, unique passwords
- Password managers
- Multi-factor authentication

A good password is the first defense — make it count. 🔐
