**NguyenQuyToanBanking.com**

Public Banking Web App – a full-featured online banking project developed by Toan Nguyen.

This application simulates real-world banking functionality, including: user accounts, money transfers, dashboards, crypto conversions, loan management, tax payments, and admin controls.

I have been working on this project for several months, continuously adding new features and improving functionality in my free time to create a comprehensive and secure banking experience.

🚀 Features

✅ User Registration & Authentication – secure login and account management

✅ Account Management & Balance Tracking – view balances and transaction history

✅ Money Transfers – send and receive money between accounts

✅ Transaction History & Dashboards – detailed overview of all activities

✅ Admin Panel – manage users, settings, and monitor activity

✅ Automated Cron Jobs – automatic profit returns and scheduled tasks

✅ Email Notifications via SMTP – for alerts and confirmations

✅ Crypto Conversion – convert balances between supported cryptocurrencies

✅ Loan Management – apply for, track, and repay loans within the app

✅ Tax Payments – calculate and pay taxes directly from the user account

🗂 Project Structure
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
| `.env.example`                                  | Change this to your .env file    |
| `Toan_Banking.sql`                              | Database export                  |



####⚙️ How to Run This Banking Web App

## How to Run This Banking Web App

### 1️⃣ Get a Domain & Hosting
- Purchase a domain name (e.g., mybankingapp.com)
- Get a hosting plan with cPanel to manage your website
- I personally use Asura Hosting  
  - Domain: $12/year  
  - cPanel hosting (manage up to 15 websites): $14/year  
  - [💻 Get Domain & Hosting (Use My Discount)](https://clients.asurahosting.com/aff.php?aff=4724)

### 2️⃣ Upload Project Files
- Download and extract the project files into your public directory or a subfolder/subdomain on your hosting account

### 3️⃣ Create Database
- In cPanel, create a new MySQL database
- Import the Toan_Banking.sql file from the database folder

### 4️⃣ Configure Environment
- Rename .env.example to .env
- Update database credentials and other settings

### 5️⃣ Setup SMTP (Email Notifications)
- Locate SMTP settings in admin and app settings
- Use default email credentials from cPanel

### 6️⃣ Optional Features
- Add LiveChat or WhatsApp code in resources/views/layouts/livechat.blade.php
- Setup cron jobs for automated profit returns

### 7️⃣ Access the Admin Panel
URL: https://yourdomain.com/auth/login  
Email: admin@admin.com  
Password: admin123

