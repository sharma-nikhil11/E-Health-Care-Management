# 🏥 E-Hospital Management System

A **console-based Java application** designed to simulate basic operations of a hospital such as managing patient data, storing diagnoses, and generating bills. This system is ideal for learning file handling in Java and understanding how command-line tools can be used to manage data.

## ✨ Key Features

### 🔐 1. Login Module
- Secures the application from unauthorized access.
- Default password: `deccan`.

### 🧾 2. Add New Patient Record
- Prompts the user to input:
  - Name, Age, Gender, Contact Info, Blood Group, and more.
- Saves the record in a `.txt` file named by the user (e.g., `john123.txt`).

### 🧪 3. Add Diagnosis Information
- Allows the doctor to:
  - Input diagnosis summary, symptoms, prescribed medicines, ward type, etc.
- Appends this data to the existing patient's file.

### 📖 4. View Patient History
- Displays all previous records from a patient’s `.txt` file.
- Helps doctors and staff track historical data.

### 💰 5. Generate Hospital Bill
- Calculates billing based on:
  - Number of days stayed
  - Ward charges
  - Doctor's fee
  - Service charges
- Appends billing info to the patient's file and displays the total amount.

### ℹ️ 6. Help Module
- Displays all the available features and how to use them.

## 🛠️ Technologies Used

| Component      | Tech           |
|----------------|----------------|
| Language       | Java           |
| I/O Handling   | FileWriter, FileReader, BufferedReader, Scanner |
| UI             | Console-based  |

## 📦 Project Structure

```bash
ehospital-system/
├── Ehospital.java       # Main Java source file
├── README.md            # Project documentation (this file)

