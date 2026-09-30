# C++ Console Banking System

A lightweight, console-based banking application built in C++ that simulates fundamental account operations like checking balances, making deposits, and withdrawing funds with built-in input validation.

## ✨ Features

* **Interactive Menu:** Clean loop-driven terminal menu allowing continuous operations until exit.
* **Core Banking Operations:**
  * **View Balance:** Displays the current account balance formatted to two decimal places.
  * **Deposit Money:** Validates inputs to ensure only positive amounts are added.
  * **Withdraw Money:** Prevents overdrafts (insufficient funds) and negative entries.
* **Robust Error Handling:** Clears input streams and ignores invalid character buffers to prevent infinite loops on bad inputs.

## 🛠️️ Technologies Used

* **Language:** C++
* **Standard Libraries:** `<iostream>`, `<iomanip>`

## 🚀 Getting Started

### Prerequisites
You need a C++ compiler installed on your machine (such as `g++`, Clang, or MSVC).

### Compilation & Execution
1. Clone the repository or copy the source code into a file named `banking.cpp`.
2. Open your terminal or command prompt and compile the code:
   ```bash
   g++ banking.cpp -o banking
