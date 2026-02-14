# ReclaimIt – Basic Lost and Found System

A simple web-based Lost and Found system where users can post and browse lost or found items.

## Tech Stack

- **Backend:** PHP (procedural PHP pages and API handlers)  
  Files: `index.php`, `config.php`, `ajax.php`
- **Frontend:** HTML, CSS, JavaScript  
  Files: `index.php`, `style.css`, `main.js`
- **Database:** MySQL (via PHP `mysqli`)  
  Configured in `config.php` and initialized through `setup_database.php`

## How to Run (Local Setup)

1. Install **XAMPP**.
2. Start **Apache** and **MySQL** from the XAMPP Control Panel.
3. Copy this project folder into:  
   `C:/xampp/htdocs/`  
   (Keep the folder name unchanged.)
4. In your browser, open:  
   `http://localhost/reclaimit-lost%20and%20found%20system/setup_database.php`  
   to automatically create the database and tables.
5. Then open:  
   `http://localhost/reclaimit-lost%20and%20found%20system/`  
   to use the system.

## Quick Note

If you are new to running PHP projects: extract the project, install XAMPP, open the folder in VS Code, and let github copilot do the work there is readme.md in there so that you can see the feautures 
