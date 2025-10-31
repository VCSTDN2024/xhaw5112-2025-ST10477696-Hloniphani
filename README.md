# Empower Web App

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/RTnyLYAE)
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/VCSTDN2024/xhaw5112-2025-ST10477696-Hloniphani)

An Android application for "Empowering The Nation" - an educational platform offering various skill development courses including First Aid, Sewing, Landscaping, Life Skills, Child Minding, Cooking, and Garden Maintenance.

## 🔗 Repository
**GitHub:** https://github.com/VCSTDN2024/xhaw5112-2025-ST10477696-Hloniphani

## 📱 App Overview

The Empower Web App provides a comprehensive mobile platform for course enrollment and fee calculation. Users can browse available courses, calculate fees with automatic discounts, and complete secure payments directly through the app.

## ✨ Features

### 🔐 Authentication
- Multiple sign-in options (Username/Password, Google, Facebook, LinkedIn, Guest)
- Input validation for username, password, and phone number
- Secure user authentication flow

### 📚 Course Management
- **Six-Month Courses (R1500 each):**
  - First Aid
  - Sewing
  - Landscaping
  - Life Skills

- **Six-Week Courses (R750 each):**
  - Child Minding
  - Cooking
  - Garden Maintenance

### 💰 Fee Calculator
- Select up to 4 courses per enrollment
- Automatic discount calculation:
  - 1 course: 0% discount
  - 2 courses: 5% discount
  - 3 courses: 10% discount
  - 4+ courses: 15% discount
- Duplicate course prevention

### 💳 Secure Payment
- Credit card validation using Luhn algorithm
- Expiry date and CVV validation
- Purchase summary with discount breakdown

### 📍 Contact Information
- Multiple campus locations with addresses
- Direct call functionality
- Google Maps integration
- Social media links (Instagram, LinkedIn, Facebook)

## 🛠️ Technical Specifications

### Requirements
- **Minimum SDK:** 24 (Android 7.0)
- **Target SDK:** 36
- **Compile SDK:** 36
- **Java Version:** 11
- **Kotlin Version:** 2.0.21

### Dependencies
- **AndroidX Core KTX:** 1.10.1
- **AppCompat:** 1.6.1
- **Material Design:** 1.10.0
- **ConstraintLayout:** 2.1.4
- **Activity:** 1.8.0

### Testing
- **JUnit:** 4.13.2
- **AndroidX JUnit:** 1.1.5
- **Espresso Core:** 3.5.1

## 🏗️ Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/empowerwebapp/
│   │   │   ├── MainActivity.kt          # Login Screen
│   │   │   ├── MainActivity2.kt         # Home Screen
│   │   │   ├── MainActivity3.kt         # Courses Screen
│   │   │   ├── MainActivity4.kt         # Calculate Fees Screen
│   │   │   ├── MainActivity5.kt         # Contact Screen
│   │   │   ├── MainActivity6.kt         # Course Information Screen
│   │   │   └── MainActivity7.kt         # Payment Screen
│   │   └── res/
│   │       ├── layout/                  # XML layouts
│   │       ├── values/                  # Colors, strings, themes
│   │       └── drawable/                # Images and icons
│   └── test/                           # Unit tests
└── build.gradle.kts                    # App-level build configuration
```

## 🚀 Getting Started

### Prerequisites
- Android Studio Arctic Fox or later
- JDK 11 or later
- Android SDK with API level 24+

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VCSTDN2024/xhaw5112-2025-ST10477696-Hloniphani.git
   cd xhaw5112-2025-ST10477696-Hloniphani
   ```

2. **Open in Android Studio:**
   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to the project directory

3. **Sync the project:**
   - Android Studio will automatically sync Gradle files
   - Wait for the sync to complete

4. **Run the app:**
   - Connect an Android device or start an emulator
   - Click the "Run" button or press `Shift + F10`

### Building the Project

```bash
# Debug build
./gradlew assembleDebug

# Release build
./gradlew assembleRelease

# Run tests
./gradlew test
```

## 📋 Usage

### Login Flow
1. Enter username (4+ letters only)
2. Enter password (8+ characters)
3. Enter phone number (10 digits starting with 0)
4. Choose sign-in method or continue as guest

### Course Enrollment
1. Navigate to "Courses" from the home screen
2. Browse available courses with detailed information
3. Use "Calculate Fees" to select up to 4 courses
4. Review pricing with automatic discounts
5. Complete secure payment process

### Contact Information
- Access campus locations and contact details
- Use direct call functionality
- Get directions via Google Maps integration

## 🎨 Design System

### Color Scheme
- **Primary:** Light Blue
- **Background:** White
- **Text:** Dark Gray/Black
- **Accent:** Material Design colors

### UI Components
- Material Design components
- Consistent navigation drawer
- Card-based layouts
- Responsive design with ConstraintLayout

## 🔒 Security Features

- Input validation on all forms
- Luhn algorithm for credit card validation
- Secure authentication flow
- Data validation for payment processing

## 📱 Screen Flow

```
Login → Home → Courses → Course Info
              ↓
         Calculate Fees → Payment
              ↓
           Contact
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support and inquiries:
- **Central Campus:** (011) 123-4567
- **North Campus:** (011) 234-5678
- **South Campus:** (011) 345-6789

## 🔗 Social Media

- [Instagram](https://instagram.com/empoweringthenation)
- [LinkedIn](https://linkedin.com/company/empoweringthenation)
- [Facebook](https://facebook.com/empoweringthenation)

---

**Empowering The Nation** - Building skills, transforming lives.
