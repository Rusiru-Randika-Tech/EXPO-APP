# Task Tracker

A simple, clean To-Do List application built with React Native and Expo.

## Features

- ✅ Add, complete, and delete tasks
- 💾 Persistent storage with AsyncStorage
- 🎨 Clean, modern UI
- 📱 Works on iOS, Android, and Web

## Getting Started

```bash
# Install dependencies
npm install

# Start the development server
npm start

# Run on specific platforms
npm run ios
npm run android
npm run web
```

## Project Structure

```
/
├── App.tsx                    # Entry point
└── src/
    ├── types/
    │   └── index.ts           # TypeScript interfaces
    ├── hooks/
    │   └── useTaskStorage.ts  # Custom hook for data management
    ├── components/
    │   ├── TaskItem.tsx       # Task row component
    │   └── AddTaskBar.tsx     # Input bar component
    └── screens/
        └── HomeScreen.tsx     # Main screen
```

## Technologies

- React Native
- Expo
- TypeScript
- AsyncStorage
- Expo Vector Icons
