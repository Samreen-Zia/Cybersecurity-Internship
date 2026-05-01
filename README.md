# Cybersecurity Internship Portfolio | Arch Technologies 🛡️

This repository showcases the technical projects and security simulations completed during my Cybersecurity Internship at **Arch Technologies**. Each task demonstrates a core competency in network security, digital forensics, or data science.

---

## 👤 Intern Information
* **Name:** Samreen Zia
* **Intern ID:** ARCH-2610-0260
* **Education:** Software Engineering Student at Fatima Jinnah Women University

---

## 🛠️ Technical Stack
* **Languages:** Python 3.11,
* **Security Tools:** Scapy (Packet Sniffing), Pynput (Event Monitoring)
* **Forensics:** Recuva v1.54 (Deep Scan & NTFS Analysis)
* **Machine Learning:** Pandas, Scikit-learn, SMOTE, Jupyter Notebooks.

---

## 📂 Project Details

### Task 1. Network Traffic Analysis (Basic Sniffer)
Developed a Python-based sniffer to capture and decode live network packets.
* **Objective:** Understand data flow and packet structures (IP, TCP, UDP).
* **Key Features:** Real-time extraction of Source/Destination IPs and Protocol identification.
* **Tools Used:** `scapy` library in Python.

### Task 2. Keylogging & Input Security
A controlled simulation of a keylogger to study the mechanics of input-based vulnerabilities.
* **Objective:** Log keystrokes to a local file to understand how spyware operates.
* **Key Features:** Stealth execution, file logging, and secure exit via the ESC key.
* **Tools Used:** `pynput` library.

### Task 3. Digital Forensics: Data Recovery
Performed a deep-dive recovery of "permanently deleted" files to demonstrate data persistence.
* **Objective:** Recover specific project files from an NTFS file system.
* **Success:** Successfully retrieved `OS_project_.pdf` using binary header recognition.
* **Tools Used:** Recuva v1.54.

### Task 4. Machine Learning for Fraud Detection
Built a predictive model to identify fraudulent financial transactions within a large dataset.
* **Objective:** Solve the "class imbalance" problem in credit card fraud detection.
* **Key Achievement:** Applied **SMOTE** for oversampling and evaluated performance using **ROC-AUC** curves.
* **Tools Used:** Python, Scikit-learn, Matplotlib.

---

## 🏗️ Repository Structure
```text
├── Task1_Network_Sniffer/    # Python scripts & traffic logs
├── Task2_Keylogger/          # Keystroke simulation source code
├── Task3_Data_Recovery/      # Forensics report & recovery evidence
└── Task4_Fraud_Detection/    # ML Notebooks & dataset documentation
