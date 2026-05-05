# IT3040 – Assignment 1

## Transliteration Accuracy Testing

### Student ID: IT23729216

---

## 📌 Project Overview

This project focuses on testing the accuracy of a Sinhala transliteration system that converts **Singlish input into Sinhala output**.

The system under test:
👉 https://www.pixelssuite.com/chat-translator

The main goal is to identify incorrect conversions (failures) using structured test cases and automation.

---

## 🎯 Objectives

* Evaluate the correctness of Singlish → Sinhala conversion
* Identify weaknesses in transliteration
* Design and execute **50 negative test cases**
* Automate testing using Playwright
* Record and analyze results

---

## 🧪 Test Case Design

* Total Test Cases: **50**
* Type: **Negative (failure cases only)**
* Coverage:

  * Question forms
  * Commands
  * Greetings
  * Slang & casual phrases
  * English mixed inputs
  * Numbers, dates, time
  * Emojis
  * URLs & emails
  * And more (24 input types)

Each test case includes:

* TC ID
* Input length (S / M / L)
* Input (Singlish)
* Expected Output (Sinhala)
* Actual Output (auto-generated)
* Status (Pass/Fail)
* Input type covered
* Evidence / rationale

---

## ⚙️ Technologies Used

* Python 3.11
* Playwright
* OpenPyXL
* Microsoft Excel

---

## 🚀 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/gajendra54-design/IT23729216.git
```

---

### 2. Install dependencies

```bash
pip install -U pip
pip install playwright openpyxl
playwright install
```

---

### 3. Run the automation script

```bash
python test_automation.py --excel "IT23729216.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---

## 📊 Results

* Results are automatically updated in the Excel file:

  * **Actual Output**
  * **Status (Pass/Fail)**

* Focus is on identifying **incorrect transliterations**

---

## 📁 Project Structure

```
IT23729216/
│── IT23729216/
│── IT23729216.xlsx
│── test_automation.py
│── README.md
```

---

## 📌 Key Findings

* The system struggles with:

  * Slang and informal language
  * Mixed English + Sinhala inputs
  * Emojis and symbols
  * Numeric formats and abbreviations

---

## ⚠️ Notes

* All test cases are uniquely created
* No examples copied from assignment appendix
* Designed to minimize plagiarism

---

## 👤 Author

**Gajendra**
Student ID: IT23729216

---
