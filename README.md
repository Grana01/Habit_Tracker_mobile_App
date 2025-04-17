# Daily Habit Tracker

A modern habit tracking app built with Kotlin that allows users to track daily habits with a clean, intuitive UI.

## Features

- **Track daily habits** with a beautiful, modern UI
- **Firebase integration** for cloud storage of habits
- **SQLite for offline storage** to track habits without internet connection
- **TabLayout with 3 tabs** for easy navigation:
  - **Track Tab:** View and mark daily habits as completed
  - **History Tab:** Display past completed habits with calendar view
  - **Settings Tab:** Manage notifications, themes, and preferences
- **Scheduled reminders** with notifications using AlarmManager
- **Modern Material UI** with custom background colors and images
- **Dark mode support**

## Technical Details

The app is built using:
- **Kotlin** language
- **MVVM architecture** with ViewModels and LiveData
- **Room Database** for SQLite storage
- **Firebase Firestore** for cloud storage
- **AlarmManager & BroadcastReceiver** for scheduled notifications
- **ViewPager2 with TabLayout** for UI navigation

## Setup

### Firebase Configuration

This app requires Firebase for cloud features. To set up Firebase:

1. Create a Firebase project at https://console.firebase.google.com/
2. Add an Android app to your Firebase project with package name `com.example.hbittrackerr`
3. Download the `google-services.json` file and place it in the `app/` directory
4. Replace the placeholder file included in this project

### Build and Run

1. Clone the repository
2. Open the project in Android Studio
3. Sync Gradle and run the app

## Screenshots

[Add screenshots here]

## License

[Your license information] 