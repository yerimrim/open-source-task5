# Space Recommendation - Open Source Practice Project

## 📌 Overview

**Space Recommendation** is a Python-based practice project designed to simulate a simple open source workflow.
This project focuses on managing **contributors** and **issues**, performing basic data analysis, and generating reports.

For detailed documentation, see `docs/project_documentation.md`.

The main purpose of this repository is:

* To practice contributing to open source projects
* To understand project structure (README, LICENSE, CONTRIBUTING, DOCUMENTATION)
* To simulate real-world collaboration scenarios

---

## 📌 Objectives
  
This project aims to help beginners:

* Understand how open source projects are structured
* Practice handling structured data (lists, dictionaries, sets)
* Learn basic file I/O operations in Python
* Simulate issue tracking and contributor management

---

## 📌 Tech Stack

* **Language:** Python
* **Concepts Used:**

  * Tuple, List, Dictionary, Set
  * List Comprehension
  * File Handling (read/write)
  * Exception Handling (try/except)
  * Basic Data Analysis

---

## 📌 Project Structure

```
.
├── main.ipynb              # Main project notebook
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── .gitignore
├── docs/
│   └── project_documentation.md  # Detailed documentation
└── space_recommendation/         # Generated after running the program
    ├── project_report.txt        # Generated report file
    └── issues.csv                # Generated issue data
```

---

## 📌 How It Works

### ✅ Section 1: Project & Contributors

* Defines project metadata using a tuple
* Collects contributor information via user input
* Stores contributors as dictionaries inside a list
* Performs operations:

  * Sorting contributor names
  * Updating contributor status
  * Copying data (backup)

---

### ✅ Section 2: Issue Tracking System

* Collects issue data from user input
* Validates input (type, priority, status)
* Stores issues as dictionaries

#### Key Features:

* Count open issues
* Update issue priority
* Extract reporters and tech stack using sets
* Perform set operations:

  * Union
  * Intersection
  * Difference
* Analyze:

  * Priority distribution
  * Status grouping
  * Top reporter

---

### ✅ Section 3: File System & Reporting

* Creates a project folder automatically
* Generates:

  * `project_report.txt` → Detailed report
  * `issues.csv` → Structured issue data

#### File Handling:

* Write data using `write()`
* Read using:

  * `read()`
  * `readline()`
  * `readlines()`

#### Error Handling:

* Handles file errors using `try/except`

---

### ✅ Final Analysis

* Prints summary of:

  * Contributors
  * Issues
  * Tech stack
  * Top reporter
  * Priority distribution

---

## 📌 How to Run

1. Clone the repository

```
git clone https://github.com/your-username/space-recommendation.git
cd space-recommendation
```

2. Run the Python file

```
python main.py
```

3. Follow the prompts to input:

* Contributor data
* Issue data

4. Check generated files:

```
space_recommendation/project_report.txt
space_recommendation/issues.csv
```

---

## 📌 Example Features Demonstrated

* Data collection from user input
* Data transformation and analysis
* File generation and persistence
* Basic simulation of:

  * Issue tracking system
  * Contributor management system

---

## 📌 Contributing

This project is created for **open source contribution practice**.

You can contribute by:

* Improving code readability
* Adding new features
* Refactoring logic
* Enhancing documentation

Please check the `CONTRIBUTING.md` file for detailed guidelines.

---

## 📌 License

This project is licensed under the **MIT License**.

---

## 📌 Notes

* This is a **learning-focused project**, not a production system
* Input is handled via interactive prompts in the notebook
* Data is not persistent beyond generated files

---

## 📌 Acknowledgement

This project was created as part of an **open source software course** to practice real-world contribution workflows.

---

## 📌 Author

* Yerim (Project Lead)

---

🙆‍♀️ *Feel free to fork, modify, and use this project for learning purposes!*

