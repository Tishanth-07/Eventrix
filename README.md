<h1 align="center">  EventTrix – Mobile-First Tech News & Event Platform </h1>

<p align="center"> <img src="/Frontend/assets/eventTrix.png" alt="EventTrix Logo" width="120"/> </p>

**EventTrix** is a modern mobile application designed to deliver **technology news and updates** to students, companies, and IT professionals. The app allows IT solutions providers to post updates, while users can **subscribe, filter content, and receive notifications in real-time**.

---

## 🔹Project Overview

EventTrix is a collaborative project developed for IEEE HackElite 2.0 – 2025.
The platform bridges the gap between students, IT professionals, and technology solution providers by delivering curated, real-time technical news and event updates.

The system enables:
- Companies & IT solution providers to publish updates.
- Users to subscribe to relevant topics and companies.
- Real-time notifications using WebSockets.
- Secure role-based access.

---

## 🔹Features

### User Authentication
- Register securely with a username and password.
- Login using **JWT authentication** to ensure secure access.
- Passwords are hashed using **bcrypt** for security.
- Role-based access (User / Provider / Admin).
- Email verification via SMTP.

### News Feed & Content Management
- IT solutions providers can post technology news and updates.
- Users can **subscribe** to specific companies, categories, or topics.
- Content can be **filtered** by category, date, or popularity for efficient browsing.
- Personalized feeds based on subscriptions.

### Notifications & Real-Time Updates
- Receive **push notifications** for new posts from subscribed sources.
- **WebSocket integration** ensures instant updates and dynamic content refresh.

### User Personalization
- Configure your preferences for notifications and subscriptions.
- Manage your account settings, including updating username or password.

### Admin & IT Solution Features
- Admins and IT solution providers can manage posts, categories, and subscriptions efficiently.
- Ensure proper content delivery and manage user subscriptions.

---

## 🔹Tech Stack

### Frontend
- React Native
- Expo Go
- Axios

### Backend
- ASP.NET (C#)
- RESTful APIs
- JWT Authentication
- WebSockets

### Database
- MongoDB

### Security & Services
- bcrypt (password hashing)
- SMTP (email verification)
- JWT tokens (authorization)

---

## 🔹Project Structure

```
HACKELITE2.0/
├── README.md
├── Frontend/
│   ├── devices.json
│   ├── README.md
│   ├── assets/
│   ├── component/
│   ├── node_modules/
│   ├── screens/
│   ├── services/
│   ├── styles/
│   ├── utils/
│   ├── AuthContext.tsx
│   ├── .env
│   ├── app.config.js
│   ├── App.tsx
│   ├── index.ts
│   ├── package-lock.json
│   ├── package.json
│   ├── tsconfig.json
│   └── .gitignore
├── Backend/
│   ├── bin/
│   ├── Controllers/
│   ├── Filters/
│   ├── Hubs/
│   ├── Models/
│   ├── obj/
│   ├── Properties/
│   │   └── launchSettings.json
│   ├── Scripts/
│   ├── Services/
│   ├── Settings/
│   ├── wwwroot/
│   ├── appsettings.Development.json
│   ├── appsettings.json
│   ├── appsettings.local.json
│   ├── Backend.csproj
│   ├── Backend.http
│   ├── build_output.txt
│   ├── msbuild.log
│   └── Program.cs
└── hackelite.sln
```
---

## 🔹Getting Started

### Install & Run
- Use **Expo Go** to run the mobile app on iOS or Android devices.
- Make sure the backend **.NET API** is running and connected to **MongoDB**.

### Register & Verify Account
- Open the app and create a new account.
- Verification emails are sent via **SMTP** to confirm user registration.
- Enter the verification code to activate your account.

### Browse & Subscribe
- Explore technology news posted by companies or IT solutions providers.
- Subscribe to categories, topics, or companies to receive targeted updates.

### Manage Preferences
- Configure notifications and subscription settings to match your interests.
- Update personal credentials securely.

### Posting News (For IT Solution Providers)
- Login as a provider/admin.
- Create, update, or delete news posts.
- Organize posts by categories for better visibility to users.

---

## 🔹Run Project 

### Run Backend (.NET API)
`dotnet restore`
`dotnet run`

Backend runs at: `https://localhost:5179`
Ensure MongoDB is running and connected.

### Run Mobile App (Expo)
`cd Frontend`
`npm install`
`expo start`

Scan QR using Expo Go
Works on Android & iOS devices

---

## 🔹Security Notes
- All sensitive user data, including passwords, are securely hashed.
- Email verification ensures only valid users can access the app.
- **JWT tokens** protect endpoints from unauthorized access.
- Users control their subscriptions and notification preferences securely.

---

This project provides a **secure and dynamic way to deliver technology news and updates** to students, companies, and IT professionals efficiently.

---

## 🔹Screenshots

<table>
  <tr>
    <td><img src="Frontend/assets/Screenshots/Screenshot1.jpeg" height="420" /></td>
    <td><img src="Frontend/assets/Screenshots/Screenshot2.jpeg" height="420" /></td>
    <td><img src="Frontend/assets/Screenshots/Screenshot3.jpeg" height="420" /></td>
  </tr>
  <tr>
    <td><img src="Frontend/assets/Screenshots/Screenshot4.jpeg" height="420" /></td>
    <td><img src="Frontend/assets/Screenshots/Screenshot5.jpeg" height="420" /></td>
    <td><img src="Frontend/assets/Screenshots/Screenshot6.jpeg" height="420" /></td>
  </tr>
  <tr>
    <td><img src="Frontend/assets/Screenshots/Screenshot7.jpeg" height="420" /></td>
    <td><img src="Frontend/assets/Screenshots/Screenshot8.jpeg" height="420" /></td>
    <td><img src="Frontend/assets/Screenshots/Screenshot9.jpeg" height="420" /></td>
  </tr>
  <tr>
    <td><img src="Frontend/assets/Screenshots/Screenshot10.jpeg" height="420" /></td>
    <td><img src="Frontend/assets/Screenshots/Screenshot11.jpeg" height="420" /></td>
    <td><img src="Frontend/assets/Screenshots/Screenshot12.jpeg" height="420" /></td>
  </tr>
</table>

---