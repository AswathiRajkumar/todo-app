Todo Task Management App -- A feature rich, cross-platform Todo Mobile App built with ReactNative(Expo) for frontend and Firebase Authentication.
Working Apk: https://expo.dev/artifacts/eas/bSL7i7Ma5hShcgs2dHwdJ9.aab
or  https://expo.dev/accounts/aswathi_006/projects/todo-app/builds/1d9e144e-30fb-4857-a0ac-ab1b542d7f4d
# Features
Email & Google Sign-In 
Add, View, Edit, and Delete Tasks
Task Priority & Due Date 
Simple & intuitive UI 

# Tech Stack
  # Frontend 
    - React Native (Expo)
    - React Navigation
    - Firebase Authentication
    - Firebase Firestore
    - AsyncStorage (for optional local storage)
    - Axios (if used for any external requests)
  # Backend
    -Firebase (Authentication) 
  # Firebase Setup
  > Follow these steps to configure Firebase for your app:

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project
3. Enable **Authentication** → **Sign-in Method** → Enable **Google**
4. Go to **Firestore Database** → Create database (in test mode)
5. In your project settings:
   - Add a new **Web App**
   - Copy the config and paste it in your `firebase/config.js` file

```js
// firebase.js

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "your-app.firebaseapp.com",
  projectId: "your-app",
  storageBucket: "your-app.appspot.com",
  messagingSenderId: "SENDER_ID",
  appId: "APP_ID"
};
Step 1: Clone the Repo
git clone https://github.com/YOUR-USERNAME/todo-native.git
cd todo-native/todo-app
Step 2: Install Dependencies
npm install
Step 3: Start Expo
npx expo start
Scan the QR code in the terminal using the Expo Go app on your phone.

# Developed By
Aswathi Rajkumar
B.Tech Computer Science and Business Systems

“This project is a part of a hackathon run by
https://www.katomaran.com"

  
