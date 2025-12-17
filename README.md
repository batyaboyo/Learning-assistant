# Learning App

## 📱 Features

*   **Interactive Roadmap**: Navigate through 4 distinct phases and 52 weeks of structured learning content.
*   **Progress Tracking**: Mark tasks and weeks as complete to track your journey.
*   **Project Portfolio**: Dedicated section to track and manage your portfolio projects (e.g., "Home Network Scan", "Smart Contracts").
*   **Quizzes**: Test your knowledge with weekly quizzes to reinforce learning.
*   **Offline Mode**: All content is stored locally using a Room database, ensuring access without an internet connection.
*   **Resources**: Curated list of free, high-quality learning resources (integrated into tasks).

## 🛠️ Tech Stack

*   **Language**: Kotlin
*   **UI Framework**: Jetpack Compose (Modern, declarative UI)
*   **Architecture**: MVVM (Model-View-ViewModel)
*   **Database**: Room (SQLite abstraction for offline persistence)
*   **Navigation**: Jetpack Navigation Compose
*   **Build System**: Gradle (Kotlin DSL)

## 🚀 How to Run

1.  **Prerequisites**: Ensure you have [Android Studio](https://developer.android.com/studio) installed.
2.  **Open Project**:
    *   Launch Android Studio.
    *   Select **Open** and navigate to this directory (`Learning-assistant`).
3.  **Sync**: Allow Gradle to sync and download dependencies.
4.  **Run**:
    *   Connect an Android device (via USB) or create an Android Virtual Device (AVD).
    *   Click the **Run** button (green play icon).

## 📂 Project Structure

*   `app/src/main/java/com/uganda/learningapp`:
    *   `data/`: Contains the Database setup, DAO, and Entities (`Module`, `Week`, `Task`, `Quiz`).
    *   `ui/`: Contains all Compose UI screens (`MainScreen`, `ProjectScreen`, `ModuleDetailScreen`, `QuizScreen`) and Theme.
    *   `MainActivity.kt`: The entry point of the application.

## 🤝 Contribution

Feel free to fork this repository and submit pull requests to add new modules, quizzes, or features!

