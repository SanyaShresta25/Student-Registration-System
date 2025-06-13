# 🎓 Student Registration System

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg?logo=python)](https://www.python.org/) [![Tkinter](https://img.shields.io/badge/Tkinter-GUI-green)]() [![Excel](https://img.shields.io/badge/Excel-OpenPyXL-orange)]() [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A sleek and efficient Python desktop app to manage student registrations with GUI and Excel integration.📑

---

## 📌 Overview

A Python-based desktop application for managing student registrations using **Tkinter** for GUI and **OpenPyXL** for Excel-based data storage. The app allows users to:

* 🧑‍🎓 Register new students
* 🖼️ Upload student images
* 🔍 Search student records
* 🛠️ Update student information
* 💾 Save data to an Excel sheet

---

## 🛠 Features

* 🎨 GUI built with Tkinter
* 📊 Stores student data in `Student_data.xlsx`
* 📝 Supports:

  * Full name
  * Class
  * Gender
  * Date of Birth
  * Religion
  * Skills
  * Parent details (name and occupation)
  * Student photo upload
* 🔎 Search functionality by Registration Number
* 🔢 Automatic Registration Number generation
* 🔁 Data update and reset options

---

## 📂 Folder Structure

```
StudentRegistrationSystem/
├── main.py
├── Student_data.xlsx         # Auto-generated
├── StudentImages/            # Stores uploaded student images
├── Images/                   # Contains UI-related image assets
│   ├── logo6.png
│   ├── pic4.png
│   ├── search.png
│   └── update.png
```

---

## 🔧 Requirements

* Python 3.x
* Libraries:

  * `tkinter` (pre-installed)
  * `openpyxl`
  * `Pillow` (PIL)

Install required libraries:

```bash
pip install openpyxl pillow
```

---

## 🚀 How to Run

1. 📥 Clone or download the project folder.
2. 📦 Install all dependencies.
3. 🖼️ Update image paths in `main.py` if needed.
4. ▶️ Run the application:

```bash
python main.py
```

---

## 🗒️ Notes

* 📁 Uploaded images are stored in the `StudentImages/` folder named as `<RegistrationNo>.png`
* 📄 If `Student_data.xlsx` does not exist, it will be created automatically on the first run.

---

## ✏️ Author

**Sanya Shresta**
📧 [sanyashresta@gmail.com](mailto:sanyashresta@gmail.com)
🔗 [GitHub – @SanyaShresta25](https://github.com/SanyaShresta25)
🌐 [Portfolio](https://sanyashresta.netlify.app/)

---

## 📄 License

Licensed under the [MIT License](https://opensource.org/licenses/MIT).
