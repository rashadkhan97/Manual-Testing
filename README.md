# Manual-Testing

This repository contains the deliverables for the manual testing project, including test cases, bug reporting, answers to various testing questions, and supporting materials like screenshots and videos. Below is the detailed breakdown of each file and its content.

## Table of Contents
- [Folder and File Descriptions](#folder-and-file-descriptions)
  - [Bug Screenshot Folder](#1-bug-screenshot-folder)
  - [Question - 02 (Feature 01).xlsx](#2-question---02-feature-01xlsx)
  - [Question - 03 (Bug Reporting).xlsx](#3-question---03-bug-reportingxlsx)
  - [Question Answer 1 2 and 5.docx](#4-question-answer-1-2-and-5docx)
- [Features Under Test](#features-under-test)
  - [Feature 1: EasyPay Merchant and Utility Bill Payments](#feature-1-easypay-merchant-and-utility-bill-payments)
  - [Feature 2: EasyPay Loan System](#feature-2-easypay-loan-system)
- [Testing Environment Details](#testing-environment-details)
- [General Activities Performed](#general-activities-performed)
- [How to Use This Repository](#how-to-use-this-repository)
- [License](#license)
- [Contributions](#contributions)

---

## Folder and File Descriptions

### 1. `Bug Screenshot` Folder
- **Contents**: 
  - Screenshots and videos for bug reporting related to Question 03.
  - These materials demonstrate the identified bugs visually.

---

### 2. `Question - 02 (Feature 01).xlsx`
- **Contents**:
  - Test cases (Positive and Negative) for **Feature 1** and **Feature 2**.
  - Detailed scenarios for validating the features under different conditions.

---

### 3. `Question - 03 (Bug Reporting).xlsx`
- **Contents**:
  - Bug reporting sheet containing at least 10 identified bugs/improvements.
  - Includes descriptions, steps to reproduce, severity, and priority for each bug.

---

### 4. `Question Answer 1 2 and 5.docx`
- **Contents**:
  - **Question Answer 1**: Acceptance criteria for Feature 1 and Feature 2.
  - **Question Answer 2**: Priority sequence for identified tasks.
  - **Question Answer 5**: Checklist for validating Feature 1 and Feature 2.

---

## Features Under Test

### **Feature 1: EasyPay Merchant and Utility Bill Payments**
- Customers can pay merchant and utility bills via the EasyPay mobile app.
- Service charge for merchant bill payments: **1% of the transaction amount**, with a minimum fee of **5 TK**.
- Cashback offers for merchant bill payments:
  - **10% cashback** for transactions over **5000 TK**.
  - **20% cashback** (maximum cashback amount: **3000 TK**) for transactions over **10,000 TK**.
- **No cashback** applies to utility bill payments.

---

### **Feature 2: EasyPay Loan System**
- Customers with balances below **100 TK** can apply for loans up to **20,000 TK**.
- Loan repayment policy:
  - No interest if the loan is repaid within **30 days**.
  - A **daily compound interest of 1.8%** is applied for overdue amounts.
  - Customers who repay at least **50%** of the remaining loan balance are eligible to apply for another loan.

---

## Testing Environment Details
- **Application URL**: [EasyPay Login](https://master.d1zgfbpp372908.amplifyapp.com/login)
- **Admin Credentials**:
  - Email: `admin@roadtocareer.net`
  - Password: `1234`
- **System User Credentials**:
  - Email: `system@roadtocareer.net`
  - Password: `1234`

---

## General Activities Performed
1. Admin can:
   - Create customers, agents, other admins, or merchants.
2. System user can:
   - Deposit money to agents.
3. Agent can:
   - Deposit or make payments to merchants.
4. Customer can:
   - Withdraw money and make payments.
5. Merchant can:
   - View the transaction history of received payments.

---

## How to Use This Repository
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/rashadkhan97/Manual-Testing.git
