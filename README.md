# Get started with Database Setup
Setup Database (XAMPP MySQL) for React App 

## Steps

1) Prerequisites
----------------
- Windows 10/11
- XAMPP (includes Apache + MySQL + phpMyAdmin)
- Python 3.10+ (recommended) and **pip**
- Node.js 18+ and "npm"

> Tip: If you already have MySQL installed elsewhere, stop it while using XAMPP’s MySQL to avoid port conflicts.

---

2) Start Services (XAMPP)
-------------------------
1. Open "XAMPP Control Panel".
2. Start "Apache" and "MySQL" (both should turn green).
3. Click "Admin" next to MySQL to open "phpMyAdmin" in the browser.

---

3) Import the Database (fyp_project.sql)
----------------------------------------
1. Go to "http://localhost/phpmyadmin".
2. Click "Databases" → Create a new database, e.g. "fyp" (utf8mb4_general_ci).
3. Select the "fyp" database (left sidebar).
4. Click "Import" → "Choose File" → select "fyp_project.sql" (top level of your project).
5. Click "Go". Wait for the success message. You should now see tables under "fyp".


