# 🌐 NguyenQuyToanBanking.com
![JavaScript](https://img.shields.io/badge/JavaScript-41.8%25-yellow) 
![CSS](https://img.shields.io/badge/CSS-33.4%25-blue) 
![Blade](https://img.shields.io/badge/Blade-19.3%25-orange) 
![PHP](https://img.shields.io/badge/PHP-4.1%25-purple) 
![HTML](https://img.shields.io/badge/HTML-0.9%25-red) 
![Hack](https://img.shields.io/badge/Hack-0.4%25-lightgrey) 
![SCSS](https://img.shields.io/badge/SCSS-0.1%25-pink)

**Public Banking Web App** – a full-featured online banking project developed by **Toan Nguyen**.

This application simulates real-world banking functionality, including user accounts, money transfers, dashboards, crypto conversions, loan management, tax payments, and admin controls. I have been working on this project for several months, continuously adding new features and improving functionality to create a comprehensive and secure banking experience.

---

## 🚀 Features

### Core Features
- ✅ **User Registration & Authentication** – secure login and account management  
- ✅ **Account Management & Balance Tracking** – view balances and transaction history  
- ✅ **Money Transfers** – send and receive money between accounts  
- ✅ **Transaction History & Dashboards** – detailed overview of all activities  

### Admin & Automation
- ✅ **Admin Panel** – manage users, settings, and monitor activity  
- ✅ **Automated Cron Jobs** – automatic profit returns and scheduled tasks  
- ✅ **Email Notifications via SMTP** – for alerts and confirmations  

### Advanced Features
- ✅ **Crypto Conversion** – convert balances between supported cryptocurrencies  
- ✅ **Loan Management** – apply for, track, and repay loans within the app  
- ✅ **Tax Payments** – calculate and pay taxes directly from user accounts  

---

## 🗂 Project Structure

| Folder/File                                     | Description                      |
| ----------------------------------------------- | -------------------------------- |
| `app`                                           | Backend logic                    |
| `routes`                                        | Routes and controllers           |
| `config`                                        | Configuration files              |
| `database`                                      | SQL scripts & backups            |
| `css` / `js` / `bootstrap` / `fonts` / `images` | Frontend assets                  |
| `dash` / `dash2`                                | User dashboards                  |
| `resources`                                     | Views and templates              |
| `storage`                                       | Storage for uploads & temp files |
| `tests`                                         | Test scripts                     |
| `.env.example`                                  | Template environment file        |
| `Toan_Banking.sql`                              | Database export                  |

---

## ⚙️ How to Run This Banking Web App

### Quick Start

1. **Get Domain & Hosting**  
   - Purchase a domain (e.g., `nguyenquybankingapp.com`)  
   - Get cPanel hosting (manage multiple websites)  
   - Recommended: **Asura Hosting**  
     - Domain: $12/year  
     - cPanel hosting: $14/year (15 hosting domains)  
     - [💻 Get Domain & Hosting (Use My Discount)](https://clients.asurahosting.com/aff.php?aff=4724)  

2. **Download Files**  
   - Download the code as a Zip file, log in to your cPanel, then find "File Manager"  

   <img width="1321" height="910" alt="image" src="https://github.com/user-attachments/assets/071d14b9-7755-45d2-8f04-594ec2eab636" />

   - Upload your Zip file to the `public_html` directory (default for your first site). Right-click the Zip file and **extract** it.  

   <img width="1918" height="911" alt="image" src="https://github.com/user-attachments/assets/72ad5ad5-8df8-4664-880c-806d5a70eb58" />

3. **Create Database**  
   - In cPanel, search for "phpMyAdmin" and click "Import" to upload the `Toan_Banking.sql` file.  
   - **Tip:** Name your database, user, and password the same for easier configuration.  
<img width="940" height="567" alt="image" src="https://github.com/user-attachments/assets/d863b5da-f7b2-4df4-b4e8-1ac4ec79b7f6" />

   <img width="1918" height="911" alt="image" src="https://github.com/user-attachments/assets/b49bd886-9fd4-40fb-9614-f3b4a58b16fb" />

4. **Configure Environment**  
   - Go back to File Manager, rename `.env.example` to `.env`  

   <img width="1916" height="910" alt="image" src="https://github.com/user-attachments/assets/5ed36e13-701b-4fc3-8b16-208122255697" />  

   - Replace the database name, user, password, and URL with your own credentials:  

   <img width="958" height="952" alt="image" src="https://github.com/user-attachments/assets/79b9b267-e7e6-4a91-9973-cc4fe22d565c" />

   - Once done, your app should be ready! Create an account to test it.  

   <img width="1918" height="1021" alt="Screenshot 2026-02-26 012000" src="https://github.com/user-attachments/assets/253cdf1e-116f-4a63-ac57-17b294a5f6fe" />  

   <img width="1907" height="908" alt="hinh3" src="https://github.com/user-attachments/assets/9db93191-6137-45f0-bc0e-971226c59d5a" />

5. **Access Admin Panel**  
   - URL: `https://yourdomain.com/auth/login`  
   - Email: `admin@admin.com`  
   - Password: `admin123`  
   - Use this panel to manage users.  

   <img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/1e51a61e-135c-4ca6-8654-05200a19564b" />

6. **Setup SMTP (Email Notifications)**  
   - Configure SMTP in admin and app settings using your cPanel credentials  

7. **Optional Features**  
   - Add LiveChat or WhatsApp code in `resources/views/layouts/livechat.blade.php`  
   - Setup cron jobs for automated profit returns  

---

✅ **Tip:** Always backup the database before making major changes.
