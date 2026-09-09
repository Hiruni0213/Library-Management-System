<div align="center">

# 📚 Library Management System

A web-based Library Management System with dedicated portals for Admins, Librarians, and Members — streamlining book cataloging, member management, and borrow/return operations.

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

---

## 📖 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [User Roles](#-user-roles)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Screenshots](#-screenshots)
- [Author](#-author)

---

## 📌 About

The **Library Management System** is a web application built to digitize and simplify day-to-day library operations. It replaces manual record-keeping with a structured system where **Admins**, **Librarians**, and **Members** each get a dedicated portal suited to their role.

## ✨ Features

- 🔐 Role-based authentication (Admin / Librarian / Member)
- 🧑‍💼 Admin dashboard for full system oversight
- 👩‍💻 Librarian portal for managing books and records
- 👤 Member portal for browsing the catalog and account access
- 📖 Book cataloging and inventory management
- 🔄 Borrow and return tracking
- 📩 Contact/messaging system for inquiries

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | PHP |
| Frontend | HTML, CSS |
| Database | MySQL |

## 👥 User Roles

| Role | Capabilities |
|---|---|
| **Admin** | Full system management and oversight |
| **Librarian** | Manage books, records, and borrow/return operations |
| **Member** | Browse catalog, manage account, contact library |

## 📁 Project Structure

```
library-management-system/
├── Images/              # Image assets
├── admin/               # Admin portal
├── authentication/      # Login & registration logic
├── config/              # Database & app configuration
├── librarian/           # Librarian portal
├── member/              # Member portal
├── about.php            # About page
├── contact.php          # Contact page
├── send_message.php     # Contact form handler
├── index.php            # Main entry point
├── about.css / index.css
└── library_db.sql       # Database schema
```

## 🚀 Getting Started

### Prerequisites

- XAMPP / WAMP (or any PHP + MySQL server environment)
- A web browser

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Hiruni0213/Library-Management-System.git
   ```
2. **Move the project** into your server's `htdocs` (or `www`) directory
3. **Set up the database**
   - Open phpMyAdmin
   - Create a new database
   - Import `library_db.sql`
4. **Configure the connection** — update credentials in the `config/` folder
5. **Start your server** — launch Apache & MySQL from your control panel
6. **Open in browser**
   ```
   http://localhost/library-management-system/
   ```

## 📸 Screenshots

> _Add screenshots of your Admin, Librarian, and Member dashboards here to showcase the UI._

| Home | Admin Dashboard | Member Portal |
|---|---|---|
| _screenshot_ | _screenshot_ | _screenshot_ |

## 👩‍💻 Author

**Hiruni Nethmini**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Hiruni0213)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hiruninethmini)

---

<div align="center">

*Developed as part of academic coursework.*

</div>
