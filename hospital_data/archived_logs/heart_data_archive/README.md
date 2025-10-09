# 🏥 Hospital Log Archival Script

## 📄 Overview
This Bash script automates the process of archiving hospital log files (such as heart rate, temperature, and water usage logs).  
It moves old log files from the **active logs** folder to the appropriate **archive folder**, renames them with a timestamp, and creates a new empty log file for continued data collection.

---

## ⚙️ Features
- Interactive menu for choosing which log to archive.  
- Automatically renames files with a timestamp to prevent overwriting.  
- Creates a new empty log file after archiving.  
- Includes error handling for missing directories or invalid input.  
- Keeps logs organized by category.

---

## 🗂️ Folder Structure
The script assumes the following directory layout inside your project:
