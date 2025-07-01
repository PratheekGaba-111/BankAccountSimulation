# 🏦 Banking System - Java Console Application

This is a simple **console-based banking system** written in Java. It uses **file handling** to manage user data and transaction history without any database. This project demonstrates object-oriented programming, exception handling, user input validation, and basic data persistence.

---

## 📂 Features

- ✅ Create a new user account  
- ✏️ Modify existing user details  
- 💵 Deposit and withdraw from an account  
- 📜 View individual transaction history  
- 📊 View all transactions (admin)  
- 🔐 Passcode-based verification for security  
- 🕒 Transaction timestamps using `LocalDateTime`

---

## 📁 Files Used

- `UserDetails.txt`: Stores all user records including `user_id`, `username`, `account number`, `balance`, and `passcode`
- `Transactions.txt`: Logs every deposit and withdrawal with `user_id`, transaction type, amount, and date

---

## ⚙️ How to Run

1. **Compile the code:**

   ```bash
   javac BankingSystem.java
   ```

2. **Run the program:**

   ```bash
   java BankingSystem
   ```

3. Follow the on-screen menu options to interact with the banking system.

---

## 📝 Menu Options

```
1. Create a new user account  
2. Modify Details of an existing user  
3. Withdraw from an account  
4. Deposit into an account  
5. Get Transaction details of an account  
6. Get Transactions of all accounts (admin)  
7. Display menu  
8. Exit  
```

---

## 📦 Project Structure

```plaintext
BankingSystem.java       → Main application file
UserDetails.txt          → Persistent user data file
Transactions.txt         → Logs of all transactions
```

---

## 🔐 Security Notes

- Passcode must be a **4-digit number** that does **not start with 0**
- Simple validation is used for account and user ID duplication
- No external database is used — all persistence is file-based

---

## 🙋‍♂️ Author

Made with ❤️ by [Pratheek Gaba]  
> Feel free to use, modify, or extend this project for learning purposes.

---

## 📌 Future Improvements

- Use a database like MySQL for storage  
- Add support for interest calculation or loans  
- Implement a GUI using Java Swing  
- Add password hashing for better security  
- Export transaction reports to PDF or CSV

---