# Bank Application

A simple **Java-based console Bank Application** that demonstrates core Java programming concepts such as **OOP, classes, objects, constructors, encapsulation, methods, conditional statements, loops, and switch-case**.

## 📌 Project Overview

The Bank Application allows a user to securely log in using a PIN and perform basic banking operations through a console-based menu.

### Features

* 🔐 PIN-based Login
* 💰 Check Account Balance
* 💵 Deposit Amount
* 💸 Withdraw Amount
* 👤 Display Account Details
* 🚪 Exit the Application
* ✅ Validation for invalid deposit and withdrawal amounts
* ⚠️ Insufficient balance validation

## 🛠️ Technologies Used

* **Programming Language:** Java
* **JDK:** Java 21
* **Input:** Java Scanner
* **Application Type:** Console-based Application

## 📂 Project Structure

```text
BankApplication/
│
├── BankApp.java
└── README.md
```

## 👤 Default Account Details

| Field           | Details    |
| --------------- | ---------- |
| Account Number  | 1001       |
| Account Holder  | Vinay jull |
| PIN             | 1234       |
| Initial Balance | ₹5000.0    |

## 🚀 How to Run

### 1. Open PowerShell

Navigate to the folder containing `BankApp.java`.

```powershell
cd Downloads
```

### 2. Compile the Java Program

```powershell
javac BankApp.java
```

If there are no errors, the Java program has been compiled successfully.

### 3. Run the Application

```powershell
java BankApp
```

## 💻 Application Flow

```text
Welcome to Bank Application

Enter PIN:
1234

Login Successful

1. Check Balance
2. Deposit Amount
3. Withdraw Amount
4. Display Account Details
5. Exit
```

## 🔄 Banking Operations

### 1. Check Balance

Displays the current account balance.

Example:

```text
Current Balance: 5000.0
```

### 2. Deposit Amount

Allows the user to deposit money into the account.

Example:

```text
Enter deposit amount:
10000

Amount Deposited Successfully
Updated Balance: 15000.0
```

### 3. Withdraw Amount

Allows the user to withdraw money if sufficient balance is available.

Example:

```text
Enter withdrawal amount:
5000

Amount Withdrawn Successfully
Updated Balance: 10000.0
```

### 4. Display Account Details

Displays the account information.

```text
Account Number: 1001
Account Holder Name: Vinay jull
```

### 5. Exit

Terminates the application.

```text
Thank you for using the Bank Application
```

## 🧠 Java Concepts Used

This project demonstrates:

* Classes and Objects
* Encapsulation
* Private Data Members
* Constructors
* Methods
* `if-else` statements
* `switch-case`
* `do-while` loop
* `Scanner` for user input
* Conditional validation
* Object creation
* Basic arithmetic operations

## 🔒 Validation

The application handles:

* Invalid PIN
* Invalid menu choice
* Invalid deposit amount
* Invalid withdrawal amount
* Withdrawal greater than available balance

## 📸 Sample Output

```text
Welcome to Bank Application
Enter PIN:
1234

Login Successful

1. Check Balance
2. Deposit Amount
3. Withdraw Amount
4. Display Account Details
5. Exit

Enter your choice:
4

Account Number: 1001
Account Holder Name: Vinay jull
```

## 🎯 Learning Objective

The main objective of this project is to understand how Java OOP concepts can be used to develop a simple real-world banking application and to practice user input, data validation, control statements, and object-oriented programming.

## 👨‍💻 Author

**Vinay jull**

Computer Science & Engineering

---

⭐ If you found this project useful, consider giving the repository a star!
