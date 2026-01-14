# 🏦 ATM Management System (Java – OOP Based)

This is a **console-based ATM Management System** developed using **Java** and designed completely with **Object-Oriented Programming (OOP) concepts**.
It simulates basic ATM operations like login, deposit, withdrawal, balance checking, and transaction history.

## 🚀 Features

* Secure login using User ID and PIN
* Deposit money
* Withdraw money
* Check account balance
* View transaction history
* Exit the system safely

---

## 🧠 OOP Concepts Used

* **Encapsulation** – User data is protected using private variables and accessed through getters/setters
* **Abstraction** – `BankOperation` abstract class defines common behavior
* **Inheritance** – `Deposit`, `Withdraw`, and `Quit` extend `BankOperation`
* **Polymorphism** – `perform()` method works differently for different operations

---

## 📁 Project Structure

```
ATMProject/
│
├── ATM.java                  → Main class (login & menu)
├── User.java                 → Stores user data securely
├── BankOperation.java        → Abstract base class
├── Deposit.java              → Deposit operation
├── Withdraw.java             → Withdraw operation
├── Quit.java                 → Exit operation
├── Transaction.java          → Stores single transaction details
└── TransactionHistory.java   → Manages transaction history
```

---

## ▶️ How to Run

### Compile:

```
javac *.java
```

### Run:

```
java ATM
```

---

## 🔐 Demo Login Details

| User ID | PIN  | Balance |
| ------- | ---- | ------- |
| 1001    | 1234 | ₹5000   |
| 1002    | 0000 | ₹1500   |

---

## 🖥 Sample Menu

```
===== ATM Menu =====
1. Deposit
2. Withdraw
3. Transaction History
4. Check Balance
5. Quit
====================
```

---

## 🎯 Learning Outcomes

* Strong understanding of OOP concepts
* Practical Java project experience
* Better preparation for placements and internships

---

## 👩‍💻 Developer

**Monica Deiveegan**
B.Tech – Information Technology
Second Year | Third Semester

---

## 🔮 Future Enhancements

* Store data in files or database
* Add new account creation
* Add PIN change feature
* Add receipt generation

---

⭐ This project is part of my journey to become a skilled software developer and get placed in a good company.
