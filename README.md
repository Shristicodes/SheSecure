# SheSecure

A mobile application built using **React Native** and **ASP.NET Core Web API** that enhances women’s safety by providing real-time location tracking, emergency alerts, and access to nearby help.

---

## 📱 Features

- 🔐 User Login/Logout with JWT Authentication
- 🗺️ Live Location Sharing using Google Maps API
- 🚨 Emergency Button with 3-second timer
- 🤝 Find nearby NGOs or helpers (Local Help)
- 🚌 Enter ride details (bus/cab info)
- 👮 Inform police after second SOS
- 👤 Profile management (edit phone, email, profile picture)
- 📩 SMS Alerts

---

## 🛠️ Tech Stack

| Layer         | Technology                  |
|--------------|-----------------------------|
| Frontend     | React Native (Expo)         |
| Backend      | ASP.NET Core Web API (C#)   |
| Database     | SQL Server / MySQL          |
| Authentication | JWT Tokens               |
| Maps         | React Native Maps + Google Maps API |
| SMS          | Twilio API                  |

---

## 🧠 Project Goals

- Empower women with a fast, reliable safety tool.
- Gain experience building a full-stack mobile application.
- Learn integrations like maps, SMS, and location tracking.

---

## 📅 Current Status

- [x] Project Planning & Design
- [x] Initial Setup (Frontend + Backend)
- [ ] Authentication Module
- [ ] Emergency Functionality
- [ ] Location Tracking
- [ ] Profile & Local Help Features

---

## 📁 Folder Structure
/women-safety-app
├── /backend
│   ├── WomenSafetyApp.API
│   │   ├── Controllers
│   │   │   └── AuthController.cs
│   │   ├── Models
│   │   │   ├── Auth
│   │   │   │   ├── LoginRequest.cs
│   │   │   │   ├── LoginResponse.cs
│   │   │   │   └── UserDto.cs
│   │   │   └── User.cs
│   │   ├── Services
│   │   │   ├── Interfaces
│   │   │   │   └── IAuthService.cs
│   │   │   └── AuthService.cs
│   │   ├── appsettings.json
│   │   └── Program.cs
│   ├── WomenSafetyApp.BLL
│   │   └── Auth
│   │       ├── Interfaces
│   │       │   └── IAuthManager.cs
│   │       └── AuthManager.cs
│   ├── WomenSafetyApp.DAL
│   │   ├── Data
│   │   │   └── AppDbContext.cs
│   │   ├── Models
│   │   │   └── User.cs
│   │   ├── Repositories
│   │   │   ├── Interfaces
│   │   │   │   └── IUserRepository.cs
│   │   │   └── UserRepository.cs
│   │   └── Migrations
│   └── WomenSafetyApp.sln
├── /frontend
│   ├── /src
│   │   ├── /assets
│   │   │   ├── /images
│   │   │   └── /fonts
│   │   ├── /components
│   │   │   └── CustomButton.js
│   │   ├── /context
│   │   │   └── AuthContext.js
│   │   ├── /navigation
│   │   │   └── AppNavigator.js
│   │   ├── /screens
│   │   │   ├── LoginScreen.js
│   │   │   ├── HomeScreen.js
│   │   │   └── SplashScreen.js
│   │   ├── /services
│   │   │   └── api.js
│   │   ├── /theme
│   │   │   └── colors.js
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
└── README.md
