# 🚀 LifeHub  

LifeHub is a **multi-functional iOS app** that combines **task management, weather updates, and finance tracking**.  
It is built using **Swift, SwiftUI, SwiftData, and Supabase**, following best practices in **iOS development, testing, and deployment**.  

🔥 This project has a fully functional GitHub Actions workflow pipeline for automated builds and tests on every push and pull request!

---

## 📌 Features  

✅ **Task Management** - Add, edit, and delete tasks, stored locally with **SwiftData**  
✅ **Weather Updates** - Fetch real-time weather using **OpenWeather API**  
✅ **Finance Tracker** - Securely track income & expenses, stored with **Supabase**  
✅ **Authentication** - User login via **Supabase Auth** (email/social login)  
✅ **Secure Storage** - Use **Keychain** to store authentication tokens  
✅ **Push Notifications** - Local notifications for task reminders  
✅ **Background Fetch** - Periodically updates weather data  
✅ **Dark Mode Support** - Full support for iOS dark mode  
✅ **Unit & UI Testing** - Automated tests with **XCTest**  

---

## 🛠️ Tech Stack & Frameworks  

| **Category**      | **Technology**  |
|------------------|---------------|
| 🖥 **Frontend** | SwiftUI, UIKit (for advanced UI) |
| 📦 **State Management** | SwiftData (CoreData alternative) |
| ☁️ **Backend** | Supabase (PostgreSQL & Auth) |
| 🔗 **Networking** | URLSession, async/await |
| 🔒 **Security** | Keychain for storing JWT tokens |
| 🌤 **API Services** | OpenWeather API (weather updates) |
| 🔔 **Notifications** | Local notifications, Background Fetch |
| 🛠 **Testing** | XCTest for unit & UI testing |
| 🚀 **CI/CD** | GitHub Actions for automated builds & tests |
| 📊 **Analytics & Logs** | Sentry (error monitoring), Google Analytics |

---

## 🏛️ App Architecture  

LifeHub follows the **MVVM (Model-View-ViewModel)** pattern for separation of concerns and better scalability.  

### **🔹 Explanation**
- **SwiftData handles local storage** for tasks & finance tracking.  
- **Supabase is used for backend data storage and authentication**.  
- **Networking (async/await) fetches weather data from OpenWeather API**.  
- **Keychain secures authentication tokens** to keep user data safe.  
- **Unit & UI tests ensure stability** before deployment.  

---

## 🚀 Getting Started  

### **📌 Prerequisites**
- **Xcode 15+**  
- **iOS 17+**  
- **Swift 5.9+**  
- **Supabase Account** (for backend)  

---

## 🎯 Roadmap

### 📌 Phase 1: Project Setup & GitHub CI/CD ✅
### 📌 Phase 2: Build UI & SwiftData Models
### 📌 Phase 3: Integrate Supabase Auth & API
### 📌 Phase 4: Implement Background Fetch & Notifications
### 📌 Phase 5: Write Unit & UI Tests

