# Manual-Testing

This repository contains the deliverables for the manual testing project, including test cases, bug reporting, answers to various testing questions, and supporting materials like screenshots and videos. Below is the detailed breakdown of each file and its content.

## Table of Contents
- [Features Under Test](#features-under-test)
  - [Feature 1: EasyPay Merchant and Utility Bill Payments](#feature-1-easypay-merchant-and-utility-bill-payments)
  - [Feature 2: EasyPay Loan System](#feature-2-easypay-loan-system)
- [Testing Environment Details](#testing-environment-details)
- [General Activities Performed](#general-activities-performed)
- [How to Use This Repository](#how-to-use-this-repository)
- [Folder and File Descriptions](#folder-and-file-descriptions)
  - [Bug Screenshot Folder](#1-bug-screenshot-folder)
  - [Question - 02 (Feature 01).xlsx](#2-question---02-feature-01xlsx)
  - [Question - 03 (Bug Reporting).xlsx](#3-question---03-bug-reportingxlsx)
  - [Question Answer 1 2 and 5.docx](#4-question-answer-1-2-and-5docx)

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

---

## Folder and File Descriptions

### 1. `Bug Screenshot` Folder
- **Contents**: 
  - Screenshots and videos for bug reporting related to Question 03.
  - These materials demonstrate the identified bugs visually.
![image](https://github.com/user-attachments/assets/14f86e7c-bf00-49d5-ac41-920d5d2f6fcd)

---

### 2. `Question - 02 (Feature 01).xlsx`
- **Contents**:
  - Test cases (Positive and Negative) for **Feature 1** and **Feature 2**.
  - Detailed scenarios for validating the features under different conditions.
- **Feature - 01**:
![image](https://github.com/user-attachments/assets/030071df-1153-465c-af14-0ac6d5f47c3a)

- **Feature - 02**:
![image](https://github.com/user-attachments/assets/1f2a0f23-c5f1-490d-864f-898f49293bd2)
  
---

### 3. `Question - 03 (Bug Reporting).xlsx`
- **Contents**:
  - Bug reporting sheet containing at least 10 identified bugs/improvements.
  - Includes descriptions, steps to reproduce, severity, and priority for each bug.
- **Bug Reporting in Excel**:
![image](https://github.com/user-attachments/assets/2d358fba-c232-494d-8b12-077f4f22994e)
![image](https://github.com/user-attachments/assets/f255aff8-de05-45f9-8c10-437ddd64e660)


---

### 4. `Question Answer 1 2 and 5.docx`
- **Contents**:
  - **Question Answer 1**: Features 1 and 2 acceptance criteria.
  - **Question Answer 2**: Priority sequence for identified tasks.
  - **Question Answer 5**: Checklist for validating Features 1 and 2.

---
