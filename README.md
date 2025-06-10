<p align="center">
  <img src="https://github.com/user-attachments/assets/7ae69be0-f3de-48d6-80ce-a89bb983ae72" alt="EdCore Logo" height="80">
  <img src="https://github.com/user-attachments/assets/71bc0532-a00d-4477-ada1-3ea86796feb2" alt="EdCore Text" height="80">
</p>

# EdCore – Learning Management System Framework

EdCore is a lightweight, PHP-based Learning Management System (LMS) framework designed to showcase multiple subjects and their associated learning materials. Originally developed as a proposal or prototype for a more complete LMS platform, it features a basic subject display interface and structured file management.

> ⚠️ Some learning materials have been removed due to copyright by STI College.

## 🌐 Demo

You can view a live version here: [https://edcore.rf.gd/](https://edcore.rf.gd/)

## 🚀 Features

- Subject listing with individual resource directories
- Basic file management (view/download)
- Lightweight and fast — no need for heavy frameworks
- Designed to be deployed on free hosting platforms

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP
- **Database:** None required (file-based system)

## 📁 Folder Structure

htdocs/
├── assets/ # Stylesheets, scripts, and static assets
├── subjects/ # Contains subject directories (e.g., Math, English)
├── index.php # Main entry point of the LMS
└── ...

bash
Copy
Edit

## 📦 Installation

1. Clone this repository:

`git clone https://github.com/altxxr0/EdCore.git`
Upload the htdocs folder to your web server (e.g., XAMPP, 000webhost, InfinityFree).

Make sure PHP is enabled and file permissions allow reading of the subjects/ directory.

Open your browser and go to `http://localhost` or your hosting domain (e.g., https://edcore.rf.gd/).

🧩 Customization
To add subjects, create folders inside the subjects/ directory.

Place PDF, DOCX, PPTX, or any resource files within those folders.

📌 Notes
This project is currently a prototype and not recommended for production without additional security layers.
Copyrighted materials from STI College were removed.

📜 License
This project is released under the MIT License.
