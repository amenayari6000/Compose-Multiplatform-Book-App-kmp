# Compose Multiplatform Book App Wkipidedia  📚

## 📌 Project Overview
This is a **Compose Multiplatform** project that targets **Android, iOS, and Desktop**, sharing both **UI and business logic** across platforms. It is built using **Jetpack Compose Multiplatform** for a unified UI and follows the **MVI architecture** with **Koin** for dependency injection.

### 🔥 Features
- **Book List** 📚: View a list of books.
- **Favorite Books** ❤️: Save books to your favorite list.
- **Search Books** 🔍: Search functionality to find books easily.
- **Detailed Book View** 📖: Get comprehensive details about a book.
- **Animations** 🎬: Smooth UI animations for an enhanced user experience.
- **Local Database** 💾: Uses **Room Database** for local storage.
- **Remote Database** 🌍: Utilizes **Ktor HttpClient** for API requests.
- **Serialization** 🔄: Ensures efficient data handling.
- **Clean Architecture** 🏗: Organized into **Domain, Data, and Presentation** layers.

## 📁 Project Structure
```
/composeApp  --> Shared code for all platforms (UI + Business Logic)
    ├── commonMain  --> Common code for Android, iOS, Desktop
    ├── androidMain --> Android-specific code
    ├── iosMain     --> iOS-specific code
    ├── desktopMain --> Desktop-specific code
/iosApp  --> iOS entry point (SwiftUI integration if needed)
/androidApp  --> Android entry point
/desktopApp  --> Desktop entry point
```

## 🚀 Running the Project
- **Android**: Run the project using **Android Studio**.
- **iOS**: You need a Mac with **Xcode** to run the iOS version.
- **Desktop**: Run the desktop target using **IntelliJ IDEA**.

## App Screenshots
### 1. Open App
<img src="https://github.com/user-attachments/assets/f141e6a8-36e6-4436-b120-ca97353d2361" width="150">

### 2. books
<img src="https://github.com/user-attachments/assets/90237009-0250-484c-9dd0-348529a89aa8" width="150">



### 3. detailed book 
<img src="https://github.com/user-attachments/assets/a280bcc1-b4ad-4db7-94b0-a73ea5907c06" width="150">


### 4. favorite 
<img src="https://github.com/user-attachments/assets/60aca311-9120-432c-88d5-a1525165a1e1" width="150">


## 🎥 Demo Video
[Watch the Demo on YouTube](https://youtu.be/2bJHTpZU5Qs)

## 📜 Long Description
This **Compose Multiplatform** application is designed for book lovers who want a seamless experience across multiple platforms. Built with **Jetpack Compose Multiplatform**, it provides a modern and intuitive UI while sharing **business logic and data handling** across **Android, iOS, and Desktop**. The **MVI architecture** ensures scalability and maintainability. **Ktor HttpClient** handles remote API calls, while **Room Database** manages local storage efficiently. With **Koin for dependency injection**, the project maintains a modular and testable codebase. This project is perfect for those looking to explore the power of **Compose Multiplatform** and **Kotlin Multiplatform** development.

## 📩 Get Started
1. Clone the repository
2. Open it in **Android Studio / IntelliJ IDEA**
3. Run the appropriate target for your platform

🔗 Happy Coding! 😊

