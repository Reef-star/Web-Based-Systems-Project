# 🐾 Pets Heaven – E-Commerce Website

**Pets Heaven** is a complete online pet supply shopping platform developed as part of the **Web-Based Systems (CIS423)** course at **Imam Abdulrahman Bin Faisal University**. It offers a streamlined and user-friendly experience for purchasing pet products like food, toys, and accessories, with both customer-facing features and admin functionalities.

This repository contains the **final version** of the project, including the full web interface, database schema, admin panel, and all required functionalities for a functioning e-commerce solution.

---

## 🧠 Project Overview

- **Purpose**: To digitize inventory and purchasing for pet supply businesses, enabling both customers and administrators to engage with the store online.
- **Technologies Used**:
  - 🖥️ HTML, CSS for frontend
  - 🐘 PHP for backend scripting
  - 🗄️ MySQL for database management
- **Platform**: Desktop-first, with attention to responsive layout and accessibility

---

## ✅ Project Status: `Completed`

- ✅ Web design and structure implemented  
- ✅ Full admin authentication system  
- ✅ Real-time product management (add, edit, delete)  
- ✅ Product browsing with dynamic detail pages  
- ✅ Shopping cart, checkout, and past purchase history  
- ✅ Contact form with embedded Google Maps  
- ✅ JavaScript form validation and help window  
- ✅ Manual testing and accessibility improvements included

---

## ✨ Final Features

- Admin login and secured dashboard  
- Dynamic product catalog with descriptions, prices, and stock tracking  
- Product add/edit/delete functionality via admin panel  
- Shopping cart with item management and checkout flow  
- “Thank You” page confirming purchases  
- Past purchase summary for returning users  
- Contact Us page with embedded location map  
- JavaScript-based form validation and help tooltips  
- Accessibility and efficiency considerations for smoother UX

---

## 🧪 Testing and Validation

- Full test cases implemented for:
  - Buying a product
  - Product management by admin
  - System login/authentication
  - Add/update/delete product workflows

---

## 📁 Project Structure

- `/html/` – Public-facing website pages (home, contact, thank-you, etc.)  
- `/admin/` – Admin login and management pages  
- `/css/` – Styling and layout sheets  
- `/images/` – Product and UI images  
- `Pets_Heaven.sql` – Full database schema and sample data

---

## 📌 Project Implications

**Solved Problems:**
- Manual inventory and product updates  
- No admin control for product changes  
- No product visibility or purchase option for customers  
- No way to track customer preferences or purchases  
- Limited reach beyond local customers

**Technical Solutions Implemented:**
- Admin portal with database-linked catalog management  
- Dynamic product listings with real-time updates  
- Purchase tracking and customer behavior insight  
- Accessibility and usability improvements

---

## 🛠️ How to Run the Project (Using XAMPP)

1. **Install XAMPP**  
   If you haven't already, download and install [XAMPP](https://www.apachefriends.org/index.html).

2. **Move Project to `htdocs`**  
   - Extract the contents of the project ZIP folder.
   - Copy the entire project folder into `C:\xampp\htdocs\`.

3. **Import the Database**  
   - Open XAMPP and start **Apache** and **MySQL**.
   - Go to `http://localhost/phpmyadmin/` in your browser.
   - Create a new database named `pets_heaven`.
   - Click **Import** and select the `Pets_Heaven.sql` file provided in the project directory.

4. **Run the Website**  
   - In your browser, go to: `http://localhost/pets_heaven/html/homepage.html`  
     or navigate to the admin login via: `http://localhost/pets_heaven/admin/admin%20authentication%20page.php`

---

## 📅 Course

**CIS423 – Web-Based Systems**  
College of Computer Science & IT, Imam Abdulrahman Bin Faisal University  
Academic Year: 2024–2025

---

## 📌 License

This project is developed for academic purposes only and is not intended for commercial use. The prototype and report are shared for educational and portfolio purposes.


