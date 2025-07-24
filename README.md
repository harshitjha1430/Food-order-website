# 🍴 Online Food Ordering System  

This is a **Food Ordering Web Application** developed as part of my learning journey with **PHP & MySQL**. The system enables users to browse food items, place orders online, and allows the admin to manage categories, food menus, and track customer orders.  

---

## **📖 Project Overview**  
The **Online Food Ordering System** is designed to simulate a real-world restaurant ordering platform:  
- **Users/Visitors** can explore food categories and place orders directly through the website.  
- **Admin** can manage all backend operations, such as updating menus, tracking orders, and managing delivery status.

This project demonstrates **full-stack web development** using **HTML, CSS, PHP, and MySQL**, running on the XAMPP server.  

---

## **⚙️ Technology Stack**  
- **Frontend:** HTML5, CSS3  
- **Backend:** Core PHP (Procedural Programming)  
- **Database:** MySQL (Relational Database)  
- **Local Server:** XAMPP (Apache + MySQL)  

---

## **✨ Features**  

### **For Users:**  
- Browse all available food categories and menu items.  
- Place food orders through a simple online interface.  

### **For Admin:**  
- Manage admin accounts.  
- Add, edit, or remove food categories and items.  
- Track and manage orders and delivery statuses.  

---

## **🚀 Installation Guide**  

### **Pre-Requisites:**  
1. Install [XAMPP](https://www.apachefriends.org/index.html).  
2. Install a text editor (VS Code, Sublime Text, Atom, etc.).  

### **Steps to Run the Project:**  
1. **Download or clone the repository**.  
2. Move the project folder to the XAMPP `htdocs` directory:  
   ```
   C:\xampp\htdocs\food-order
   ```  
3. **Start Apache and MySQL** from the XAMPP Control Panel.  
4. **Import the database:**  
   - Open `phpMyAdmin` in your browser.  
   - Create a new database (e.g., `food-order`).  
   - Import the provided SQL file.  
5. **Update configuration:**  
   - Open `config/constants.php`.  
   - Update the following constants if needed:  
     ```php
     define('SITEURL', 'http://localhost/food-order/');  
     define('LOCALHOST', 'localhost');  
     define('DB_USERNAME', 'root');  
     define('DB_PASSWORD', '');  
     define('DB_NAME', 'food-order');  
     ```  
6. Open the project in your browser:  
   ```
   http://localhost/food-order/
   ```

---

## **📂 Project Structure**  
```
food-order/
│
├── admin/          # Admin dashboard files
├── config/         # Configuration and database constants
├── images/         # Food and category images
├── css/            # Stylesheets
├── index.php       # Homepage
└── ...
```

---

## **💡 Future Enhancements**  
- Add user login and order history.  
- Implement payment gateway integration.  
- Improve responsive design for mobile devices.  
- Email notifications for order confirmations.  

---

## **🙌 Acknowledgements**  
This project is inspired by online food ordering platforms and built for educational purposes to practice **PHP and MySQL development**.
