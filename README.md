# Weather
A modern Android weather app built with Kotlin, Room, Coroutines, and Google Maps. It fetches real-time weather data using OpenWeather API, shows current conditions with icons, and stores unique cities locally. Features include location-based updates, foreground service, and a clean UI with RecyclerView.

🌤️ Weather App

A modern Android weather application built with Kotlin that provides real-time weather updates using the OpenWeather API
. The app features location-based weather, city search, and unique city storage with Room Database.

✨ Features

🌎 Current Location Weather – Get instant weather updates using device location

🏙️ Saved Cities – Save multiple unique cities and view their weather at a glance

📌 Google Maps Integration – Display city location with map markers

🔔 Foreground Service – Keeps weather service running with notifications

🗄️ Room Database – Stores weather data locally with unique city constraints

🎨 Modern UI – Clean layout with RecyclerView, Coil image loading, and Material Design

🛠️ Tech Stack

Language: Kotlin

Architecture: MVVM (ViewModel + Coroutines + Flow)

Database: Room

Location: FusedLocationProviderClient

Networking: Retrofit + Coroutines

UI: RecyclerView, MapView, Coil for images

Foreground Service: Android 14+ compatible with FOREGROUND_SERVICE_LOCATION
