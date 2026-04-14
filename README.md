# FreeMedia - Social Media App

A unique social media mobile application where **posts are permanent** - they cannot be deleted or edited once uploaded.

## Features

- 📱 **Mobile App** - Built with React Native + Expo
- 🔐 **Email Authentication** - Secure login with Firebase Auth
- 💾 **Real-time Database** - Powered by Firebase RTDB
- 🔒 **Permanent Posts** - Posts cannot be deleted or edited
- 👤 **User Profiles** - View your permanent post history
- 🎨 **Modern UI** - Clean and intuitive interface

## Tech Stack

- React Native (Expo)
- Firebase Authentication
- Firebase Realtime Database (RTDB)
- React Navigation

## Installation

1. Download the APK from [Releases](https://github.com/Anitaarista/freemedia-app/releases)
2. Enable "Unknown Sources" in Android Settings > Security
3. Open the APK file and tap "Install"

## Setup Firebase (Required)

Before using the app, you need to:

1. **Enable Authentication:**
   - Go to Firebase Console > Authentication > Sign-in method
   - Enable "Email/Password"

2. **Set Database Rules:**
   - Go to Firebase Console > Realtime Database > Rules
   - Copy the rules from `database-rules.json` file

3. **Get API Key:**
   - Go to Firebase Console > Project Settings > Your Apps
   - Add your API key to the app configuration

## Project Structure

```
freemedia-app/
├── App.js                 # Main app entry
├── src/
│   ├── config/
│   │   └── firebase.js    # Firebase configuration
│   ├── context/
│   │   └── AuthContext.js # Authentication state
│   ├── screens/
│   │   ├── LoginScreen.js
│   │   ├── RegisterScreen.js
│   │   ├── HomeScreen.js
│   │   ├── CreatePostScreen.js
│   │   ├── ProfileScreen.js
│   │   └── SettingsScreen.js
│   ├── components/
│   │   └── PostCard.js
│   └── utils/
│       └── constants.js
└── assets/
```

## License

MIT License

## Author

Created with ❤️ using React Native and Firebase
