# ✨ Bank Account Management System (Python)

---

## 🔍 Overview
Welcome to the **Bank Account Management System**! This Python-based project simulates core banking operations, allowing you to manage accounts, perform transactions, and analyze financial activity. It's a perfect demonstration of Python’s power and flexibility, using:
- Variables & Data Structures
- Functions
- File Handling
- Modules & Libraries

Whether you're learning Python or showcasing your skills, this project has everything to impress! 🚀

---

## 🔄 Key Features

### 1. 💼 Account Management
- **Create New Accounts** with:
  - Account Holder's Name
  - Auto-Generated 11-Digit Account Number
  - Account Type (Savings or Current)
  - Initial Balance
- **Retrieve Account Details**, including:
  - Account Holder’s Name
  - Account Number
  - Account Type
  - Current Balance

### 2. ⚖️ Transactions
- **Deposit Money**: Add funds to your account.
- **Withdraw Money**: Safely withdraw, ensuring sufficient balance.
- **Transfer Funds**: Seamlessly transfer money between accounts with validation.
- **Automated Balance Updates** for all transactions.

### 3. 📂 Persistent File Storage
- **Save Account Details** and Transaction History using the `pickle` library.
- **Auto-Load Data** on program startup and update seamlessly on exit.
- Append transactions to prevent overwriting historical records.

### 4. 🕐 Transaction Reports
- **Detailed Transaction History** for any account:
  - Date
  - Transaction Type (Deposit, Withdrawal, Transfer)
  - Amount
  - Target Account (if applicable)
- **Summary Statistics** for accounts:
  - Total Deposits
  - Total Withdrawals
  - Average Transaction Amounts (using `NumPy` functions).

### 5. 🚀 User-Friendly Interaction
- **Interactive Menu** for smooth navigation:
  1. Open New Account
  2. View Account Details
  3. Deposit Money
  4. Withdraw Money
  5. Transfer Money
  6. View Transaction History
  7. View Summary Statistics
  8. Exit the Program
- **Loops & Conditional Statements** for seamless user experience.

### 6. ⚠️ Error Handling
- **Input Validation** for:
  - Positive Deposit and Withdrawal Amounts
  - Sufficient Balance for Withdrawals or Transfers
  - Non-Existent Accounts
- Prevent crashes with robust error-handling mechanisms.

### 7. 🔐 Bonus Features (Optional)
- Multi-user Login with secure username and password.
- Utilize **Lambda Functions** for quick calculations and advanced operations.

---

## 🏢 Installation

### Prerequisites
Ensure you have the following installed:
- Python **3.8+**
- Required Libraries:
  - `NumPy` (Install via `pip install numpy`)
  - `pickle` (Built-in)

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bank-account-management.git
   ```
2. Navigate to the project folder:
   ```bash
   cd bank-account-management
   ```
3. Run the program:
   ```bash
   python main.py
   ```

---

## 🔧 How to Use

Launch the program to access an **interactive menu**. Choose from:

1. **Open a New Account**: Provide your details to create an account.
2. **View Account Details**: See account information and balances.
3. **Deposit Money**: Add funds to your account.
4. **Withdraw Money**: Take out money safely.
5. **Transfer Funds**: Move money between accounts.
6. **View Transaction History**: See past transactions.
7. **View Summary Statistics**: Get account performance insights.
8. **Exit**: Save all data and exit the system.

---

## 📊 Project Structure

```plaintext
bank-account-management/
├── main.py          # Entry point of the application
├── account.py       # Contains account-related classes and functions
├── transactions.py  # Handles deposits, withdrawals, and transfers
├── reports.py       # Generates transaction history and statistics
├── data/            # Stores serialized account and transaction data
├── README.md        # Project documentation
```

---

## 📢 Contributions
We welcome contributions to enhance this project! To contribute:
1. Fork this repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---

## 🌟 Acknowledgments
This project was inspired by the idea of making banking operations accessible through Python. Special thanks to the open-source community for their resources and support!

---

## 🎨 License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify it as per your needs.

---

Let’s build a seamless banking experience together! 💸

