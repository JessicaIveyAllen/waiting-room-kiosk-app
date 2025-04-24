# 🏥 Waiting Room Kiosk App

## 📱 Overview
A React Native application built with Expo that serves as a waiting room management system for offices, clinics, and other service providers. The app allows patients to check in, view their waiting status, and provides staff with tools to manage the queue.

## ✨ Features
- 📝 **Patient Check-In**: Simple form for collecting patient information
- 🆕 **New Patient Registration**: Additional fields for first-time visitors
- ⏱️ **Wait Time Tracking**: Real-time updates on wait duration
- 👀 **Privacy Mode**: Toggle between showing full names or anonymous patient numbers
- 🔐 **Staff Portal**: Password-protected admin interface
- 📊 **Queue Management**: Call in patients and mark appointments as complete

## 🛠️ Tech Stack
- React Native / Expo
- AsyncStorage for data persistence
- React Navigation for tab navigation
- Context API for state management

## 🏗️ Project Structure
```
waiting-room-kiosk-app/
├── app/               # Main app screens
├── assets/            # Images, fonts, etc.
├── components/        # Reusable UI components
├── constants/         # App configuration and constants
├── hooks/             # Custom React hooks
│   └── useWaitingList.js  # AsyncStorage implementation
├── context/           # React Context providers
│   └── WaitingListContext.js
├── scripts/           # Helper scripts
├── app.json           # Expo configuration
└── package.json       # Dependencies
```

## 📋 Next Steps
✅ Project setup and EAS CLI installation
✅ Basic project structure creation
✅ AsyncStorage implementation for data persistence
🔄 Convert Check-In tab from React web to React Native
🔄 Convert Status tab to React Native
🔄 Convert Admin tab to React Native
🔄 Implement tab navigation
🔄 Test on device using Expo Go
🔄 Add notifications and alerts
🔄 Finalize UI/UX and styling

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/waiting-room-kiosk-app.git
cd waiting-room-kiosk-app

# Install dependencies
npm install

# Install AsyncStorage
npx expo install @react-native-async-storage/async-storage

# Install Navigation
npm install @react-navigation/native @react-navigation/bottom-tabs
npx expo install react-native-screens react-native-safe-area-context

# Start the development server
npx expo start
```

## 📱 Usage
1. Scan the QR code with Expo Go (Android) or Camera app (iOS)
2. Use the bottom tabs to navigate between screens:
   - Check In: For patients to register
   - Wait Status: For patients to check their position in queue
   - Staff: Admin portal for managing patients

## 🔐 Admin Access
Default password: `1234` (Remember to change in production)

## 💾 Data Persistence
All patient data is stored locally using AsyncStorage. No server backend is required.

---

Happy coding! 🚀# waiting-room-kiosk-app
