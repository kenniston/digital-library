<div align="center">

  <img alt="Digital Library" src="assets/digital-library.jpg"/>

  <h1></h1>
  <h3>Digital Library with Python</h3>

  ![python](https://badgen.net/badge/python/3.12.3/blue?scale=1.0)
  ![pip](https://badgen.net/badge/pip/26.0.1/green?scale=1.0)
  <br/>
  [![GitHub stars](https://img.shields.io/github/stars/kenniston/digital-library.svg?style=social&label=Star&maxAge=1)](https://github.com/kenniston/digital-libary/)
  <br>Support us with a ⭐ !

</div>


# 📚 Digital Library <!-- omit from toc --> <!-- toc-omit -->

The Digital Library is a Python-based application designed to manage and simulate the lending of digital books.
The system provides core functionalities for catalog management, user interaction, and loan control, following 
clean code principles and modular design.

This project represents the first iteration of the system and is intended for internal testing and validation.

## 📋 Table of Contents <!-- omit from toc --> <!-- toc-omit -->
 
* [📖 Overview](#-overview)
* [⚙️ Features](#-features)
  * [📖 Book Management](#-book-management)
  * [👤 User Management](#-user-management)
  * [🔄 Loan System](#-loan-system)
  * [📊 Statistics & Reports](#-statistics--reports)
  * [✅ Data Validation & Consistency](#-data-validation--consistency)
* [🛠️ Installation](#-installation)
  * [🐍 Environment Setup](#-environment-setup)
    * [🔗 Clone the repository](#-clone-the-repository)
    * [📦 Install Python (>= 3.12)](#-install-python--312)
    * [🧪 Create Virtual Environment (venv)](#-create-virtual-environment-venv)
    * [▶️ Activate Virtual Environment](#-activate-virtual-environment)
    * [📌 Upgrade pip (optional but recommended)](#-upgrade-pip-optional-but-recommended)
    * [📦 Project Dependencies](#-project-dependencies)
  * [🚀 Start the Jupyter Notebook](#-start-the-jupyter-notebook)
* [📄 License](#-license)
* [🤝 Contributing](#-contributing)
* [📝 Changelog](#-changelog)


## 📖 Overview

The Digital Library is a Python-based application designed to manage and simulate the lending of digital books 
through an intuitive graphical interface. The system was developed with a strong focus on clean architecture, 
code quality, and maintainability.

The project follows a modular structure, separating responsibilities across different components to improve 
readability, scalability, and ease of testing. Additionally, the implementation adheres to the SOLID principles, 
ensuring that each part of the system has a clear and single responsibility, is extensible, and remains loosely 
coupled.

For the user interface, the application leverages:

* Tkinter for core GUI functionality
* ttkbootstrap for modern styling and enhanced visual components

The codebase follows the PEP 8 Style Guide to maintain consistency and readability across the project:
👉 https://peps.python.org/pep-0008/

This combination of design principles and technologies results in a well-structured, maintainable, and scalable 
foundation for future enhancements.


---
## ⚙️ Features

### 📖 Book Management
   - 📚 Register books (Title, Author, Year, ISBN, Category)
   - 🗂️ Data stored using lists and dictionaries
   - 🔍 Search by title, author, or category
   - 🚫 Prevent duplicate ISBNs

### 👤 User Management
   - 🧑‍💻 Register users (Name, Email, ID, Type)
   - 🏷️ Types: Student, Professor, Visitor
   - 📦 Data stored with lists and dictionaries
   - 🔒 Email uniqueness ensured using sets

### 🔄 Loan System
   - 🔗 Associate books with users
   - 📅 Track loan dates
   - ⛔ Prevent borrowing unavailable books
   - 📋 List all active loans

### 📊 Statistics & Reports
   - 📈 Books per category
   - 👥 Loans per user type
   - 🏆 Most borrowed books

### ✅ Data Validation & Consistency
   - ✔️ Required fields validation
   - 🚫 No duplicate ISBNs
   - 🔄 Correct loan/return state updates


---
## 🛠️ Installation

### 🐍 Environment Setup

#### 🔗 Clone the repository

```bash
git clone https://github.com/kenniston/digital-library
cd digital-library
```

#### 📦 Install Python (>= 3.12)

Make sure you have Python 3.12 or higher installed:

- **Linux (Ubuntu/Debian)**
  ```bash
  sudo apt update
  sudo apt install python3.12 python3.12-venv python3.12-dev
  ```

- **macOS (Homebrew)**
  ```bash
  brew install python@3.12
  ```

- **Windows**
 
  > Download and install from the official website: 👉 https://www.python.org/downloads/
  > 
  > ⚠️ Make sure to check "Add Python to PATH" during installation.

<br/>

---
#### 🧪 Create Virtual Environment (venv)
Navigate to your project directory and run:

```bash
python3.12 -m venv .venv
```

---
#### ▶️ Activate Virtual Environment

- **Linux / macOS**
```bash
source .venv/bin/activate
```

- **Window (PowerShell)**
```bash
.venv\Scripts\Activate.ps1
```

- **Window (PowerShell)**
```bash
.venv\Scripts\Activate.ps1
```

- **Window (CMD)**
```bash
.venv\Scripts\Activate.ps1
```

---
#### 📌 Upgrade pip (optional but recommended)
```bash
pip install --upgrade pip
```

---
#### 📦 Project Dependencies

Install all required project packages from `requirements.txt` after activating the virtual environment:

```bash
pip install -r requirements.txt
```

To confirm the dependencies were installed successfully:

```bash
pip list
```

---
### 🚀 Start the Jupyter Notebook

After setting up and activating your virtual environment, install Jupyter and open the notebook:

```bash
pip install notebook
jupyter notebook src/main.ipynb
```

If you only want to start Jupyter and choose the file in the browser:

```bash
jupyter notebook
```

---
## 📄 License
  
Licensed under either of

- Apache License, Version 2.0 (LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
- MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)

at your option.


## 🤝 Contributing

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

Contributions are welcome! Join us — let’s build the future of Rust together.

Here's how to get started:

1. **🍴 Fork** the repository
2. **🔧 Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **💾 Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **📤 Push** to the branch (`git push origin feature/amazing-feature`)
5. **🔀 Open** a Pull Request


## 📝 Changelog
  
  👉 See [CHANGELOG.md](CHANGELOG.md) for version history and updates.
