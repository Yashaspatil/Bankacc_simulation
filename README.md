# 💳 BankAccount SMS Notification System

This Python project simulates a simple bank account system with deposit and withdrawal functionality. It uses [Twilio](https://www.twilio.com/) to send SMS alerts and Python’s built-in `logging` module to track transactions and errors.

## 📦 Features

- Create a bank account with an initial balance
- Withdraw funds (with insufficient funds check)
- Deposit funds (with validation)
- Send SMS alerts for all transactions
- Log all activities to `bank_transactions.log`

## 🔧 Technologies Used

- Python 3.x
- Twilio Python SDK
- Logging module

## 📁 File Structure

## 📲 Prerequisites

1. Python 3 installed
2. [Twilio account](https://www.twilio.com/) with:
   - Account SID
   - Auth Token
   - Verified phone number
3. Install dependencies:

```bash
pip install twilio
self.account_sid = 'your_twilio_account_sid'
self.auth_token = 'your_twilio_auth_token'
self.twilio_number = '+1XXXXXXXXXX'
INFO:root:Account created: 123456, Initial balance: ₹1000
INFO:root:Withdrawal of ₹500.00 successful. Available balance: ₹500.00 (Account: 123456)
WARNING:root:Withdrawal failed: Insufficient funds for withdrawal (Account: 123456)
INFO:root:Account created: 123456, Initial balance: ₹1000
INFO:root:Withdrawal of ₹500.00 successful. Available balance: ₹500.00 (Account: 123456)
WARNING:root:Withdrawal failed: Insufficient funds for withdrawal (Account: 123456)
