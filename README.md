# Flutter Home Screen Widget
A Flutter project demonstrating how to create **home screen widgets** for Android, based on the official Google codelab.

[![Google Developer Badge](https://img.shields.io/badge/Google%20Developer-Learning%20Badge-blue?logo=google)](https://developers.google.com/profile)
[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart)](https://dart.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Overview
The app displays a list of news articles. A home screen widget shows the title, description, and a chart of the selected article.

## Features
- News article list
- Android home screen widget
- Widget update from the Flutter app
- Display a Flutter chart as an image in the widget
- Data sharing via SharedPreferences (home_widget package)

## Tech Stack
| Technology | Usage |
|------------|-------|
| Flutter | Main framework |
| Dart | Programming language |
| Kotlin | Native Android code |
| home_widget ^0.9.0 | Flutter and Widget communication |
| shared_preferences ^2.5.4 | Local storage |
| Genymotion | Android emulator |

## Installation
### Prerequisites
- Flutter SDK installed
- Genymotion or an Android device
- VSCode or Android Studio

### Steps
```bash
git clone https://github.com/AB-060/flutter-homescreen-widget.git
cd flutter-homescreen-widget
flutter pub get
flutter run
```

## Completed Codelab Steps
| Step | Description | Status |
|------|-------------|--------|
| 3 | Create a basic home screen widget | ✅ |
| 4 | Send Flutter data to the widget | ✅ |
| 6 | Display a Flutter widget as an image | ✅ |

## How to Test the Widget
1. Run the app with `flutter run`
2. On Genymotion or Android Studio, **long press** the home screen
3. Select **Widgets** and search for **homescreen_widgets**
4. Add the widget to the home screen
5. Open an article in the app and tap **Update Homescreen**
6. The widget displays the title, description, and chart!

## Google Developer Badge
This project was completed as part of the official Google codelab:
[Adding a Home Screen widget to your Flutter App](https://codelabs.developers.google.com/flutter-home-screen-widgets)

Learning badge earned on April 3, 2026

## Resources
- [Flutter Documentation](https://docs.flutter.dev)
- [home_widget package](https://pub.dev/packages/home_widget)
- [Official Google Codelab](https://codelabs.developers.google.com/flutter-home-screen-widgets)
- [Android App Widgets Documentation](https://developer.android.com/develop/ui/views/appwidgets)

## Author
**Abdallahi**
- GitHub: [AB-060](https://github.com/AB-060)
- Google Developer Profile: [My Profile](https://me.developers.google.com/u/115985114902930184863)
