# 🏦 Bank Account Simulator

## 📌 Project Objective

The Bank Account Simulator is a console-based Java application developed to understand and implement Object-Oriented Programming (OOP) concepts. The project simulates basic banking operations such as account creation, deposits, withdrawals, balance inquiry, and transaction history while following clean code and industry-standard package structure.

---

## ✨ Features

- Create Customer
- Create Bank Account
- Support Savings Account
- Support Current Account
- Deposit Money
- Withdraw Money
- Check Account Balance
- View Transaction History
- Auto Generate Account Number
- Auto Generate Customer ID
- Auto Generate Transaction ID
- Input Validation
- Console-Based User Interface

---

## 📚 Classes

### Model
- Customer
- BankAccount (Abstract)
- SavingsAccount
- CurrentAccount
- Transaction
- DepositTransaction
- WithdrawTransaction

### Service
- BankService

### Utility
- AccountGenerator

### Main
- Main

---

## 🔗 Relationships

### HAS-A Relationship

- Customer HAS-A BankAccount
- BankAccount HAS-A Transactions

### IS-A Relationship

- SavingsAccount IS-A BankAccount
- CurrentAccount IS-A BankAccount
- DepositTransaction IS-A Transaction
- WithdrawTransaction IS-A Transaction