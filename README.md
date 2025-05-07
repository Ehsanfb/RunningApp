# RunningApp 🏃‍♂️

A modern Android application built with Kotlin and Jetpack libraries that tracks your running activities. It uses Google Maps to track your route in real time, stores your run data locally, and displays statistics like distance, speed, and calories burned.

## Features

- 📍 Live location tracking with Google Maps API  
- 📊 Run statistics: time, distance, average speed, and calories burned  
- 📅 Sort runs by date, duration, distance, and average speed  
- 💾 Local data storage using Room database  
- ⏱️ Stopwatch functionality during runs  
- 📈 Charts to show running progress (MPAndroidChart)  
- 🔐 Runtime permissions handling  
- 🚀 MVVM architecture with Kotlin Coroutines and Flow  
- ✅ Dependency Injection with Dagger-Hilt

## Tech Stack

- **Language**: Kotlin  
- **Architecture**: MVVM (Model-View-ViewModel)  
- **UI**: XML, Material Design  
- **Asynchronous Tasks**: Kotlin Coroutines & Flow  
- **Database**: Room  
- **Dependency Injection**: Dagger Hilt  
- **Location Tracking**: Google Maps API  
- **Charts**: MPAndroidChart  
- **Other**: Glide (for image loading), Navigation Component, Service & BroadcastReceiver

## Screenshots

(Add screenshots of the app here if you'd like)

## How to Run

1. Clone this repo
2. Open it in Android Studio
3. Add your Google Maps API key in `google_maps_api.xml`
4. Build and run the app on a physical device (location permissions required)

## License

This project is created for learning and personal development purposes.
