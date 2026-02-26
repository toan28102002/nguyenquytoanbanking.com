# 🌐 NguyenQuyToanBanking.com

## 🛠 Languages & Technologies Used

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
   - Purchase a domain (e.g., `mybankingapp.com`)  
   - Get cPanel hosting (manage multiple websites)  
   - Recommended: **Asura Hosting**  
     - Domain: $12/year  
     - cPanel hosting: $14/year  
     - [💻 Get Domain & Hosting (Use My Discount)](https://clients.asurahosting.com/aff.php?aff=4724)  

2. **Upload Project Files**  
   - Extract files into your public directory or subfolder/subdomain on your hosting account  

3. **Create Database**  
   - In cPanel, create a MySQL database  
   - Import `Toan_Banking.sql`  

4. **Configure Environment**  
   - Rename `.env.example` to `.env`  
   - Update database credentials and other settings  

5. **Setup SMTP (Email Notifications)**  
   - Configure SMTP in admin and app settings  
   - Use default email credentials from cPanel  

6. **Optional Features**  
   - Add LiveChat or WhatsApp code in `resources/views/layouts/livechat.blade.php`  
   - Setup cron jobs for automated profit returns  

7. **Access Admin Panel**  
   - URL: `https://yourdomain.com/auth/login`  
   - Email: `admin@admin.com`  
   - Password: `admin123`  

---

## 🔗 Links

- Portfolio: [toanportfolio.com](https://toanportfolio.com)  
- Banking App Demo: [NguyenQuyToanBanking.com](https://nguyenquytoanbanking.com)  

### Test Account
- **Account:** `user1`  
- **Password:** `toanbanking`  
- **PIN:** `1234`  

---

✅ **Tip:** Always backup the database before making major changes.
