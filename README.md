# 💫 Bhavya Sri's Portfolio

Welcome to my personal portfolio website! This is a simple yet elegant web application designed to showcase who I am, the projects I’ve worked on, and how you can reach out to me.

---

## 🧠 About Me

Hi! I'm **Bhavya Sri**, a passionate CSE student who loves turning ideas into digital reality. I enjoy working with web technologies, solving real-world problems, and constantly learning new things.

---

## 🌐 Website Overview

This portfolio highlights:
- ✨ A clean homepage with quick navigation
- 📸 An image gallery
- 🧰 A projects/portfolio section
- 📬 A functional contact form connected to a MySQL database using PHP

---

## 🚀 Tech Stack

| Tech        | Description                      |
|-------------|----------------------------------|
| HTML5       | Structure                        |
| CSS3        | Styling                          |
| PHP         | Backend scripting                |
| MySQL       | Database integration             |
| Bootstrap   | (Light usage) for UI enhancements|

---

## 📩 Contact Form Setup (Local)

If you want to run this locally with full functionality:

1. **Install [XAMPP](https://www.apachefriends.org/)** and start Apache + MySQL.
2. Place the project folder (`bhavyaport`) inside the `htdocs/` directory.
3. Import this MySQL table:
   ```sql
   CREATE TABLE contact_messages (
       id INT AUTO_INCREMENT PRIMARY KEY,
       name VARCHAR(100) NOT NULL,
       email VARCHAR(100) NOT NULL,
       message TEXT NOT NULL
   );
