# 🚀 Expression Evaluation in C

This repository demonstrates how tricky expressions with **pre-increment (`++x`)**, **post-increment (`x++`)**, and **multiple updates of the same variable** behave in C.

⚠ **Important:**  
These expressions cause **undefined behaviour** in C/C++. That means the result is compiler-dependent.  
The step-by-step explanation below shows one **possible evaluation order** (tested with GCC/Turbo C).

---
