# 🔐 Cyber Threat Database

## 📌 Description

Cyber Threat Database is a beginner-friendly **C++ cybersecurity project** that allows users to store, view, and search information about different cyber threats.

The project uses a text file to save threat information such as **threat name, type, severity, and description**.

## 🎯 Objectives

* Store information about cyber threats.
* Display all stored threats.
* Search for a specific threat.
* Categorize threats based on their type and severity.
* Learn basic file handling in C++.

## ⚙️ Features

* ➕ Add a new cyber threat
* 📋 Display all threats
* 🔍 Search for a threat
* ⚠️ Record threat severity
* 📝 Store threat descriptions
* 💾 Save data permanently in a text file

## 🛠️ Technologies Used

* **Language:** C++
* **IDE:** Dev-C++
* **Concepts:** File Handling, Functions, Strings, Loops, Conditional Statements

## 📂 Project Structure

```text
Cyber-Threat-Database/
│
├── CyberThreatDatabase.cpp
├── threats.txt
└── README.md
```

## ▶️ How to Run

1. Open **Dev-C++**.
2. Open `CyberThreatDatabase.cpp`.
3. Compile and run the program.
4. Select an option from the menu.
5. Add, display, or search cyber threats.
6. The threat information is stored in `threats.txt`.

## 💻 Sample Output

```text
========================================
          CYBER THREAT DATABASE
========================================
1. Add Threat
2. Display All Threats
3. Search Threat
4. Exit
----------------------------------------
Enter your choice: 1

Enter Threat Name: Ransomware
Enter Threat Type: Malware
Enter Severity (Low/Medium/High): High
Enter Description: Encrypts files and demands payment

Threat added successfully!
```

## 📄 Data Format

Threat information is stored in the following format:

```text
Threat Name | Threat Type | Severity | Description
```

Example:

```text
Ransomware|Malware|High|Encrypts files and demands payment
Phishing|Social Engineering|Medium|Attempts to steal sensitive information
Trojan|Malware|High|Malicious software disguised as a legitimate program
```

## 📚 Concepts Learned

* C++ File Handling
* `ifstream` and `ofstream`
* String manipulation
* Functions
* Loops
* Conditional statements
* Searching data in files
* Basic cybersecurity concepts

## ⚠️ Disclaimer

This project is created for **educational purposes only**. The threat information stored in the database is for demonstration and learning purposes.

## 👩‍💻 Author

**Sanjana Mallick**

B.Tech CSIT – Cybersecurity

