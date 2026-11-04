RockPaperSnap ✊✋✌️

An interactive Mobile Application built using React Native and Expo Router for the Mobile Application Development module (COST 32152).

📱 Features

Interactive Game Engine: Play Rock, Paper, Scissors against an automated computer opponent with live scoreboard tracking (Wins, Draws, Losses).

Tab Navigation: File-based navigation using Expo Router with smooth switching between Play Game and Rules tabs.

Custom UI & Styling: Styled with React Native Flexbox, dynamic theme color indicators, vector icons, and custom splash screen configuration.

📌 Summary

🛠️ What I Did

Created an Expo Router project (RockPaperSnap) and configured custom splash screen settings in app.json.

Implemented core game logic in src/app/(tabs)/index.tsx using useState for choices, dynamic outcomes, and scoreboard counters.

Built a scrollable rules page in src/app/(tabs)/rules.tsx outlining game winning conditions.

Set up tab navigation ((tabs)/\_layout.tsx) and root layout (\_layout.tsx) using Expo Router and Ionicons.

Configured EAS Build to compile and generate a standalone Android APK.

💡 What I Learned

React State Management: Handling complex state updates with useState for live UI rendering.

Expo Router: Building file-based tab and stack navigation structure.

Advanced Flexbox: Styling responsive layouts, score cards, and interactive weapon buttons in React Native.

App Deployment: Managing splash assets and configuring native Android builds via EAS CLI.

🚀 Getting Started

Prerequisites

Node.js installed on your machine.

Expo Go app on your mobile device (for live preview).

Quick Run

# 1. Install dependencies

npm install
npx expo install @expo/vector-icons

# 2. Start Expo server with clear cache

npx expo start -c

Scan the QR code printed in the terminal using Expo Go (Android) or the default Camera app (iOS).

📦 Project Structure

RockPaperSnap/
├── assets/images/ # App splash icon (appIcon.png)
├── src/app/
│ ├── \_layout.tsx # Root Stack layout
│ └── (tabs)/
│ ├── \_layout.tsx # Tab navigation setup
│ ├── index.tsx # Main Play Screen logic
│ └── rules.tsx # Game Rules screen
└── Output_Screens/ # Screenshots for submission

🛠️ Tech Stack

Framework: React Native (Expo Router)

Language: TypeScript / JavaScript

Build Tool: EAS CLI (Android APK)

Icons: @expo/vector-icons (Ionicons)
