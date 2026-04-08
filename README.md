# Flutter Counter App (Persistent Storage)

This project is a simple Flutter counter application built as part of Week 2 of my internship.

## 📱 Features
- Increment and decrement counter
- Real-time UI updates using `setState`
- Persistent storage using `SharedPreferences`

## 🛠️ Tech Stack
- Flutter
- Dart
- SharedPreferences (for local storage)

## 🚀 How It Works
1. The app loads the saved counter value from local storage on startup.
2. User can:
   - Increase the counter
   - Decrease the counter
3. Every change is saved using `SharedPreferences`.
4. When the app restarts, the saved value is retrieved and displayed.

## 📂 Project Structure
- `home_screen.dart` → Contains counter logic, UI, and storage handling
- `main.dart` → Entry point of the app

## ▶️ How to Run
1. Clone the repository
2. Run:


## 🎯 Learning Outcomes
- Understanding `setState` for state management
- Using `SharedPreferences` for persistent data storage
- Handling asynchronous operations (`async` / `await`)
- Managing app lifecycle with `initState()`

## 👨‍💻 Author
Faraz Sarwar