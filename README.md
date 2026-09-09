#  Library Management System

A web-based Library Management System with separate portals for Admins, Librarians, and Members — supporting book cataloging, member registration, and borrow/return operations.

## Features

-  Authentication system for different user roles (Admin, Librarian, Member)
-  **Admin** portal for overall system management
-  **Librarian** portal for managing books and library operations
-  **Member** portal for browsing and interacting with the library catalog
-  Book cataloging and management
-  Borrow/return tracking
-  Contact/messaging functionality

## Tech Stack

- **Backend:** PHP
- **Frontend:** HTML, CSS
- **Database:** MySQL

## Project Structure

```
library-management-system/
├── Images/              # Image assets
├── admin/               # Admin portal files
├── authentication/      # Login/registration logic
├── config/              # Database & app configuration
├── librarian/           # Librarian portal files
├── member/              # Member portal files
├── about.php            # About page
├── contact.php          # Contact page
├── index.php            # Main entry point
├── send_message.php     # Contact form handler
├── about.css / index.css
└── library_db.sql       # Database schema
```

## Getting Started

### Prerequisites

- XAMPP
- Web browser

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/Hiruni0213/Library-Management-System.git
   ```
2. Move the project folder into your server's `htdocs` (or `www`) directory
3. Open **phpMyAdmin**, create a new database, and import `library_db.sql`
4. Update the database connection credentials in the `config/` folder
5. Start Apache & MySQL from your XAMPP/WAMP control panel
6. Open your browser and navigate to:
   ```
   http://localhost/Library system
   ```

## User Roles

| Role | Access |
|------|--------|
| Admin | Full system management |
| Librarian | Manage books, borrow/return records |
| Member | Browse catalog, view account, contact library |

## Author

**Hiruni Nethmini**
- GitHub: [@Hiruni0213](https://github.com/Hiruni0213)
- LinkedIn: [Hiruni Nethmini](https://linkedin.com/in/hiruninethmini)

## License

This project was developed for academic purposes.
