# weatherapp_starter_project

A new Flutter project.

## Overview
This is a simple weather app built using Flutter. It allows users to enter the name of a city and view its current weather information.

## Features
- Display current weather information (temperature, weather condition, humidity, etc.).
- Fetch weather data from a weather API.
- Support for multiple cities.
- Basic error handling for network and user input errors.
- Prerequisites
- Flutter SDK installed (compatible with the latest Flutter version).
- An API key from a weather service provider. (In this example, we will use OpenWeatherMap API)

## Setup
**Clone this repository:**
```bash
git clone <repository-url>
```
Create a file named secrets.dart inside the lib folder with your API key:

dart
```bash
// lib/secrets.dart
class Secrets {
  static const String openWeatherMapApiKey = 'YOUR_API_KEY_HERE';
}
```

## Install dependencies:
```bash
flutter pub get
\\Run the app
```
```bash
flutter run
```

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
