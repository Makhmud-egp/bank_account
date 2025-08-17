# 🏦 BankAccount Project (beginner-friendly)

A simple Python class that simulates a bank account with deposit, withdraw, and balance check.

## Features
- Create a new bank account with an owner and initial balance
- Deposit money into the account
- Withdraw money safely (no overdrafts)
- Check the balance

## Example Usage

```python
from bank_account import BankAccount

acc = BankAccount("Ali", 100)
acc.deposit(50)      # Deposited 50. New balance = 150
acc.withdraw(30)     # Withdrew 30. New balance = 120
acc.get_balance()    # 💰 Balance = 120
