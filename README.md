# 🏙️ Smart City Guide

**Smart City Guide** is a Java-based application designed to store and present essential city information—helping newcomers easily discover local facilities, attractions, and services.

---

## 🌟 Why Smart City Guide?

Every year, countless people move to new cities for jobs, education, or a better lifestyle. But in those first few weeks, simple questions arise:

- Where can I find essential services?
- What are the must-see attractions?
- Which areas have the facilities I need?

**Smart City Guide** solves this problem by providing a centralized, easy-to-use platform where users can **store**, **search**, and **explore** city information.

---

## 🚀 Features

- **🏠 Add Places** – Enter new points of interest with details like name, address, category, and description.
- **🔍 Search** – Quickly find places by name or category.
- **📋 Display All** – View the full list of stored locations at a glance.
- **💾 Persistent Storage** – Information is saved locally for future use.
- **🖥️ Simple GUI** – Intuitive interface built with Java Swing.

---

## 🛠️ Tech Stack

- **Language**: Java
- **UI Toolkit**: Java Swing
- **Storage**: Local text file (places.txt)

---

## 📂 Project Structure

| File                  | Description |
|-----------------------|-------------|
| `Main.java`           | Entry point to the application |
| `SmartCityGuide.java` | Core logic, GUI, and file handling |
| `CategoryClass.java`  | Handles category definitions |
| `searchClass.java`    | Implements search functionality |
| `Accounts.java`       | Manages user/account data |
| `Image.png`           | Project illustration or reference |

---

## 🏁 Getting Started

### Prerequisites
- Java Development Kit (JDK) installed
- No external libraries required

### Run Locally
```bash
git clone https://github.com/Renukanarayan/Smart_City_Guide.git
cd Smart_City_Guide
javac *.java
java SmartCityGuide
