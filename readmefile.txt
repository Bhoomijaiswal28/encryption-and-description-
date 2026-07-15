

# 📌 Project Overview

This project is a **Caesar Cipher Encryption and Decryption Program** developed in **Python** as part of my **Cyber Security Internship**.

The Caesar Cipher is one of the oldest and simplest encryption techniques used in classical cryptography. It encrypts a message by shifting each alphabet character by a fixed number of positions (called the **Key** or **Shift Value**).

The objective of this project is to understand the basic principles of:

- Information Security
- Data Confidentiality
- Encryption
- Decryption
- Cryptography Fundamentals
- Secure Programming Logic

Although Caesar Cipher is not secure for modern applications, it is an excellent project for beginners to understand how encryption algorithms work.

---

# 🎯 Objectives

- Learn the fundamentals of Cryptography.
- Understand Encryption & Decryption.
- Implement Caesar Cipher Algorithm.
- Develop logical thinking using Python.
- Practice Functions, Loops and String Manipulation.
- Understand how data can be protected using encryption.

---

# ✨ Features

✅ Encrypt Plain Text

✅ Decrypt Cipher Text

✅ User-defined Shift Key

✅ Handles Lowercase Letters

✅ Preserves Spaces

✅ Beginner Friendly Code

✅ Console Based Application

✅ Fast Execution

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3 | Programming Language |
| VS Code | Code Editor |
| Git | Version Control |
| GitHub | Project Hosting |

---

# 📂 Project Structure

```
Caesar-Cipher/
│
├── caesar_cipher.py
├── README.md
└── screenshots/
      ├── encryption.png
      └── decryption.png
```

---

# ⚙️ How Caesar Cipher Works

The Caesar Cipher shifts every letter by a fixed number.

For example,

If the Key = **3**

```
A → D
B → E
C → F
...
X → A
Y → B
Z → C
```

### Example

Original Text

```
HELLO
```

Shift Key

```
3
```

Encrypted Text

```
KHOOR
```

Again shifting backward by **3** gives

```
HELLO
```

---

# 🔄 Algorithm

## Encryption

1. Take user input.
2. Take Shift Key.
3. Find the index of each letter.
4. Add the shift key.
5. Wrap around using modulo (%).
6. Display Cipher Text.

---

## Decryption

1. Take Cipher Text.
2. Take Shift Key.
3. Find index of each letter.
4. Subtract Shift Key.
5. Wrap around using modulo (%).
6. Display Original Text.

---

# 💻 Program Workflow

```
              Start
                 │
                 ▼
     Select Encrypt / Decrypt
                 │
                 ▼
          Enter Shift Key
                 │
                 ▼
          Enter User Text
                 │
                 ▼
      Perform Caesar Cipher Logic
                 │
                 ▼
       Display Final Output
                 │
                 ▼
                End
```

---

# 🚀 Installation

Clone this repository

```bash
git clone https://github.com/yourusername/Caesar-Cipher.git
```

Go to project folder

```bash
cd Caesar-Cipher
```

Run

```bash
python caesar_cipher.py
```

---

# ▶ Example Output

## Encryption

```
*** CAESAR CIPHER PROGRAM ***

Do you want to encrypt or decrypt?

e/d : e

Enter Key : 5

Enter Text :

hello world

Cipher Text :

mjqqt btwqi
```

---

## Decryption

```
*** CAESAR CIPHER PROGRAM ***

Do you want to encrypt or decrypt?

e/d : d

Enter Key : 5

Enter Text :

mjqqt btwqi

Plain Text :

hello world
```

---

# 📚 Concepts Used

- Cryptography
- Caesar Cipher
- Encryption
- Decryption
- ASCII Characters
- String Manipulation
- Functions
- Loops
- Conditional Statements
- User Input
- Python Programming

---

# 🔒 Why Encryption is Important

Encryption converts readable information into unreadable data.

It helps in

- Protecting Sensitive Information
- Secure Communication
- Maintaining Data Confidentiality
- Preventing Unauthorized Access
- Improving Cyber Security

---

# ⚠ Limitations

- Supports only alphabet characters.
- Uses Classical Encryption.
- Vulnerable to Brute Force Attack.
- Not suitable for modern secure communication.

---

# 🔮 Future Improvements

- GUI using Tkinter
- File Encryption
- Uppercase Support
- Password Protection
- Multiple Encryption Algorithms
- Vigenère Cipher
- AES Encryption
- RSA Encryption
- Save Encrypted Files
- Dark Theme Interface

---

# 🧪 Testing

The project has been tested with

✔ Small Sentences

✔ Long Paragraphs

✔ Different Shift Keys

✔ Spaces

✔ Numbers

✔ Special Characters

---

# 📈 Learning Outcomes

After completing this project, I learned:

- Fundamentals of Cryptography
- Caesar Cipher Implementation
- Encryption Process
- Decryption Process
- Python Functions
- String Handling
- Programming Logic
- Problem Solving
- Cyber Security Basics

---

# 📖 Internship Project

This project was developed as part of my **Cyber Security Internship**, where the objective was to implement a basic encryption and decryption technique using the Caesar Cipher algorithm to understand the fundamentals of cryptography and secure communication.

---


