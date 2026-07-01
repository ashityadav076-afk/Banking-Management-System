# Bank Management System (C++)

## Overview

This project is a console-based **Bank Management System** developed in **C++** using Object-Oriented Programming (OOP) principles. It simulates fundamental banking operations, allowing users to create an account, manage transactions, calculate compound interest, and evaluate loan eligibility based on predefined credit score criteria.

The application provides a menu-driven interface and demonstrates the practical implementation of classes, constructors, destructors, encapsulation, and mathematical computations in C++.

## Features

* Create a bank account with an initial balance and interest rate.
* Deposit money into the account.
* Withdraw money while maintaining a minimum account balance.
* Calculate compound interest for a specified number of years.
* Display the current account balance.
* Check loan eligibility using a rule-based credit score and loan amount evaluation.
* Interactive menu-driven console interface.

## Technologies Used

* **Language:** C++
* **Concepts:** Object-Oriented Programming (OOP), Classes, Constructors, Destructors, Encapsulation
* **Libraries:** `<iostream>`, `<cmath>`, `<unistd.h>`

## Project Structure

* **Bank Class**

  * Account creation
  * Deposit and withdrawal operations
  * Compound interest calculation
  * Balance inquiry

* **Loan Class**

  * Credit score validation
  * Loan eligibility assessment
  * Rule-based approval system

## How It Works

1. The user creates a bank account by providing an initial balance and interest rate.
2. A menu allows the user to perform various banking operations.
3. Deposits and withdrawals update the account balance while enforcing a minimum balance requirement.
4. Compound interest is calculated using the entered time period.
5. Users can verify loan eligibility based on predefined credit score thresholds and requested loan amounts.
6. The application terminates when the user chooses to close the account.
