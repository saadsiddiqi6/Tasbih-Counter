# Tasbih Counter - Android Application

A spiritual counter application for Android with lock screen support and volume button integration.

## Features

✅ **Volume Button Control**
- Volume Up: Increment counter
- Volume Down: Reset counter
- Works in app and on lock screen

✅ **Persistent Storage**
- Room Database for reliable data persistence
- Automatic save on every action

✅ **Clean Architecture**
- MVVM pattern with ViewModel
- Repository pattern for data management
- LiveData for reactive UI updates

✅ **User-Friendly Interface**
- Material Design 3 UI
- Large counter display
- Touch buttons for controls

## Technical Stack

- Kotlin
- MVVM Architecture
- Room Database
- Material Design 3
- Coroutines
- Min SDK: 21
- Target SDK: 34

## Project Structure

```
app/src/main/
├── java/com/tasbih/counter/
│   ├── data/
│   │   ├── TasbihCount.kt
│   │   ├── TasbihDao.kt
│   │   └── TasbihDatabase.kt
│   ├── repository/
│   │   └── TasbihRepository.kt
│   ├── viewmodel/
│   │   └── TasbihViewModel.kt
│   ├── ui/
│   │   └── MainActivity.kt
├── res/
│   ├── layout/
│   │   └── activity_main.xml
│   ├── values/
│   │   ├── colors.xml
│   │   ├── strings.xml
│   │   └── styles.xml
│   └── drawable/
│       └── counter_background.xml
└── AndroidManifest.xml
```

## Building & Running

1. Clone the repository
2. Open in Android Studio
3. Sync Gradle files
4. Run on emulator or device

## Usage

- **Volume Up**: Increment counter
- **Volume Down**: Reset counter
- **+1 Button**: Manual increment
- **Reset Button**: Manual reset

## License

MIT License
