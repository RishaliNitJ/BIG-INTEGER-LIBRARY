# 🔢 Big Integer Library

A custom C++ library to perform arithmetic and mathematical operations on **large integers (up to 100 digits)** that exceed standard data type limits.

---

## 🚀 Overview

Standard C++ data types like `int` and `long long` cannot handle very large numbers.
This library provides an efficient way to perform operations on big integers using custom implementations.

---

## ✨ Features

* ➕ Addition of large integers
* ➖ Subtraction of large integers
* ✖️ Multiplication
* ➗ Division
* 🔁 Modulus operation
* 📊 GCD (Greatest Common Divisor)
* 📈 LCM (Least Common Multiple)
* 🔢 Factorial of large numbers

---

## 🛠️ Tech Stack

* **Language:** C++
* **Concepts Used:**

  * Object-Oriented Programming
  * Operator Overloading
  * Arrays / Strings for number storage

---

## ⚙️ How It Works

* Large integers are stored as strings or arrays
* Arithmetic operations are implemented manually (digit-by-digit)
* Mathematical functions are built using these core operations

---

Example:

```cpp
BigInt a = "12345678901234567890";
BigInt b = "98765432109876543210";

cout << a + b << endl;
cout << gcd(a, b) << endl;
```
## 🌟 Future Improvements

* Support for larger integers
* Optimization for faster computations
* Add more mathematical functions

---
## 👩‍💻 Author

**Rishali **

---

## ⭐ If you like this project

Give it a star ⭐
