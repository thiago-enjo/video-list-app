# VideoListApp
VideoListApp is an Android application developed with Kotlin and Jetpack Compose.  
It demonstrates modern Android development practices by displaying a list of videos from a REST API and playing them using ExoPlayer, supporting streaming formats such as HLS and DASH.

## Features
- Display a scrollable list of videos using LazyColumn.  
- Navigate smoothly between list and player screens using Navigation Compose.  
- Fetch data from a REST API using Retrofit and Coroutines.  
- Implement MVVM architecture with ViewModel and Repository pattern.  
- Play video streams with ExoPlayer.  
- Manage UI state asynchronously with StateFlow.  
- Basic error handling for network requests and video playback.

## Technologies
- Kotlin  
- Jetpack Compose  
- Android Architecture Components (ViewModel, Navigation)  
- Retrofit + Coroutines  
- ExoPlayer  
- Hilt

- ## Project Structure
```
app/
├── data/ # Data sources, API and repositories
├── ui/ # Screens and Jetpack Compose components
├── viewmodel/ # ViewModels for MVVM
└── di/ # Dependency injection setup
```

## How to Run
### Prerequisites
- **Android Studio Giraffe (2022.3.1) or later**
  Required for full support of Jetpack Compose, Kotlin 1.8+, and the latest Android build tools compatible with Android Studio Giraffe.

- **JDK 17 or later**
  Needed to compile the project with Android Gradle Plugin 8+ and to ensure compatibility with modern Kotlin features.

- **Android emulator (API 30+) or physical device**
  API 30 (Android 11) is the recommended minimum for testing modern Android apps. A physical device is recommended for better performance, especially when testing video playback with ExoPlayer.

### Steps
1. Clone the repository: `git clone https://github.com/your-username/VideoListApp.git`
2. Open the project in Android Studio.
3. Wait for Gradle to sync.
4. Run the app on an emulator or a connected device.

## Project Purpose
This project was created to practice modern Android development techniques. It includes:
- Kotlin and Jetpack Compose for building the UI
- REST API integration for fetching video data
- MVVM architecture with Repository pattern
- Version control setup with Git and GitHub
