<<<<<<< HEAD
# Introduction 
TODO: Give a short introduction of your project. Let this section explain the objectives or the motivation behind this project. 

# Getting Started
TODO: Guide users through getting your code up and running on their own system. In this section you can talk about:
1.	Installation process
2.	Software dependencies
3.	Latest releases
4.	API references

# Build and Test
TODO: Describe and show how to build your code and run the tests. 

# Contribute
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)
=======
# Glamour Cuts

A salon booking and management system built for XISD5319 (Group 19).

## About

Glamour Cuts lets clients book salon appointments online and gives staff a
dashboard to manage bookings. The project includes both a website and a
native Android mobile app.

## Team

Role & Name 
Developer / Project Manager | Maselelo Alicia Mabelebele (ST10436039)
Business Analyst | Lufuno Makhado (ST10442357)
Technical Lead / QA | Tiyase Damaris Nteseng (ST10445279) 

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP 8.2
- **Database:** Firebase Firestore
- **Mobile App:** Kotlin (native Android)
- **Mobile Backend:** Firebase Realtime Database
- **Email:** PHPMailer + Gmail SMTP
- **Hosting:** Microsoft Azure (planned)

## Features

- Online appointment booking with email confirmation
- Staff login and appointment dashboard
- WhatsApp quick-contact button
- Mobile app: booking, team chat, inventory management, reviews, analytics
- Role-based access (client / stylist, with admin approval for stylists)

## Setup

1. Clone this repo into your XAMPP `htdocs` folder
2. Run `composer install` to install PHP dependencies (PHPMailer, Firebase SDK)
3. Add your own `firebase-credentials.json` (Firebase service account key) and
   `mail_config.php` (Gmail app password) — see `.gitignore` for excluded files
4. Start Apache via XAMPP and visit `index.php`

## Project Structure

```
glamour-cuts/
├── index.php              # Homepage + booking form
├── booking_process.php    # Handles booking submission + email
├── login.php              # Staff login
├── dashboard.php          # Staff appointment dashboard
├── logout.php
├── db.php                 # Firestore connection
├── PHPMailer/             # Email library
├── assets/                # Images/logo
└── mobile-app/            # (Android app — see separate repo/folder)
```
>>>>>>> 5457da476104b24517ba13ef00974d19af3da1df
