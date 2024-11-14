# 📖 get_next_line - Reading lines one by one

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue.svg" alt="Language C">
  <img src="https://img.shields.io/badge/School-42-black.svg" alt="School 42">
  <img src="https://img.shields.io/badge/Score-125%2F100-success.svg" alt="Score">
  <img src="https://img.shields.io/badge/Concept-Static%20Variables-purple.svg" alt="Static Variables">
</p>

> *"Because `read()` doesn't care about `\n`."*

## 🌟 About the Project

**get_next_line** is a fundamental project at **School 42**. The objective is simple but challenging: write a function that returns a single line read from a file descriptor. 

This project is a deep dive into **static variables**, buffer manipulation, and rigorous memory management (avoiding memory leaks at all costs). Calling the function in a loop will read the text file completely, line by line.

## 🚀 Features & Bonus

This repository includes the **Bonus Part** of the subject, which brings major upgrades:
* **Multi-FD support:** It can manage multiple file descriptors simultaneously. You can read from `fd 3`, then `fd 4`, then `fd 3` again, without losing the reading thread of either file.
* **Single static variable:** The bonus is completely implemented using only one static variable.
* **Custom Buffer Size:** The buffer size used for `read()` can be modified at compile time using the `-D BUFFER_SIZE=n` flag.

## 🛠️ Usage

**1. Clone the repository:**
```bash
git clone [https://github.com/YOUR_USERNAME/get_next_line.git](https://github.com/YOUR_USERNAME/get_next_line.git)
cd get_next_line
