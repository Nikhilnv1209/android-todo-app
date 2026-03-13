# TodoApp

A simple Todo application built with Android and Jetpack Compose.

## Features

- Create, read, update, and delete todo items
- Clean UI built with Jetpack Compose
- Material Design 3 components

## Tech Stack

- **Language:** Kotlin
- **UI Framework:** Jetpack Compose
- **Architecture:** TBD
- **Build System:** Gradle with Kotlin DSL

## Project Structure

```
app/
├── src/main/java/com/example/todoapp/
│   ├── MainActivity.kt          # Main entry point
│   └── ui/theme/                # App theme (colors, typography, theme)
├── src/main/res/                # Resources (layouts, drawables, values)
├── src/androidTest/             # Instrumented tests
└── src/test/                    # Unit tests
```

## Getting Started

### Prerequisites

- Android Studio (latest stable version)
- JDK 17 or higher
- Android SDK

### Build & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Nikhilnv1209/android-todo-app.git
   ```

2. Open the project in Android Studio

3. Sync Gradle and run the app on an emulator or physical device

## Building

```bash
# Debug build
./gradlew assembleDebug

# Release build
./gradlew assembleRelease
```

## Running Tests

```bash
# Unit tests
./gradlew test

# Instrumented tests
./gradlew connectedAndroidTest
```

## License

TBD
