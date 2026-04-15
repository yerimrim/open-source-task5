# Documentation – Space Recommendation Project

## 📌 1. Introduction

This document provides a **detailed, beginner-friendly guide** to understanding and using the **Space Recommendation** project.

This project is a **Python-based simulation** of an open source workflow, including:

* Contributor management
* Issue tracking
* Data analysis
* Report generation

It is designed for **learning purposes**, especially for students who are new to open source contribution.

For a high-level overview, see README.md.

---

## 📌 2. Who Is This For?

This documentation is written for:

* Beginners in Python
* Students learning open source workflows
* Anyone who wants to understand how simple project management systems work

No prior experience with open source is required.

---

## 📌 3. Requirements

Before running the project, make sure you have:

### ✅ Required

* Python 3.x installed

### Check Python installation

Open terminal (Mac/Linux) or command prompt (Windows):

```
python --version
```

If installed correctly, you will see something like:

```
Python 3.x.x
```

---

## 📌 4. Setup

### Step 1: Download the project

#### Option A: Using Git (recommended)

```
git clone https://github.com/your-username/space-recommendation.git
cd space-recommendation
```

#### Option B: Manual download

1. Click **Code → Download ZIP**
2. Extract the folder
3. Open the folder in your terminal

---

## 📌 5. How to Run the Program

### Option A: Using Jupyter Notebook

1. Open `main.ipynb`
2. Run all cells in order
3. Follow the prompts to input data

### Option B: Convert to Python script (optional)

If converted to `.py` file:

---

## 📌 6. Program Structure (Step-by-Step)

---

### ✅ Section 1: Project & Contributors

#### What happens here?

* Project information is stored in a **tuple**
* User inputs contributor information
* Data is stored in a **list of dictionaries**

#### Example Input

```
Name: Yerim
Role: Junior Developer
Language: Python
Commits: 10
Country: Republic of Korea
```

#### What the program does:

* Sorts contributor names
* Adds `"status": "Active"` to each contributor
* Creates a backup copy of data

---

### ✅ Section 2: Issue Tracking

#### What happens here?

You will input issue information.

#### Example Input

```
Id: 1
Title: 404 Error
Type: Bug
Priority: Critical
Reporter: James
Status: Open
```

#### Input Rules (VERY IMPORTANT)

* Type → must be `Bug` or `Feature`
* Priority → must be:

  * Critical
  * High
  * Medium
  * Low
* Status → must be:

  * Open
  * In Progress
  * Resolved

If you enter invalid input, the program will ask again.

---

#### What the program analyzes:

* Number of open issues
* Priority distribution
* Reporter list
* Top reporter (who reported most issues)

---

### ✅ Section 3: File Creation & Reports

#### What happens here?

The program automatically creates:

```
space_recommendation/
```

Inside this folder:

### 1. project_report.txt

Contains:

* Project info
* Contributor list
* Issue list
* Analysis results

### 2. issues.csv

Contains structured issue data:

```
id, title, priority, reporter, status
```

---

#### File Handling Features

The program demonstrates:

* Writing files (`write`)
* Reading files:

  * `read()`
  * `readline()`
  * `readlines()`
* Error handling with `try/except`

---

### ✅ Section 4: Final Summary Output

At the end, the program prints:

* Total contributors
* Total issues
* Open issues count
* Tech stack
* Top reporter
* Priority summary

---

### ✅ Section 5: Urgent Issues Feature

#### What is considered urgent?

* Issues with:

  * `Critical`
  * `High` priority

#### What happens?

* Extracts urgent issues
* Appends them to:

```
project_report.txt
```

---

## 📌 7. Example Output Files

### project_report.txt

```
======= Project Info =======
Project : Space Recommendation   Version : 1.0   Lead : Yerim

======= Contributors =======
Contributors : 4   Names : ['Yerim', 'James', 'Bob', 'Chloe']
```

---

### issues.csv

```
id, title, priority, reporter, status
1, 404 Error, Critical, James, Open
```

---

## 📌 8. Common Errors & Solutions

### Error: invalid input keeps repeating

Cause: wrong format (e.g., typing "bugg")

✔ Solution:

* Use exact values:

  * Bug / Feature
  * Critical / High / Medium / Low
  * Open / In Progress / Resolved

---

### Error: file not created

Cause: permission issue or folder already exists

✔ Solution:

* Check folder permissions
* Re-run the program

---

### Error: Python not found

✔ Solution:

* Install Python from https://www.python.org/

---

## 📌 9. What You Learn From This Project

* Data structures in Python
* Input validation
* File I/O operations
* Basic data analysis
* Open source workflow structure

---

## 📌 10. Next Steps

After understanding this project, you can:

* Add new features (e.g., UI, database)
* Improve validation logic
* Refactor code for better readability
* Practice contributing via pull requests

---

## 📌 11. Summary

This project is a **complete beginner-friendly simulation** of:

* Contributor management
* Issue tracking
* Data analysis
* File-based reporting

It is ideal for practicing **open source contribution workflows**.

---

## 🙆‍♀️ Final Note

If you can run this project and understand each section,
you are ready to start contributing to real open source projects.
