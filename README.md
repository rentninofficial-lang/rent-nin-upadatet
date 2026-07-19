# RentNin — Native Android Application

RentNin is a modern, high-fidelity verified rental property portal for Bangladesh. Built natively in **Kotlin** and **Jetpack Compose** using Material Design 3 guidelines.

## Features

- **Explore Dashboard**: Premium hero section, popular neighborhoods (Gulshan, Banani, Dhanmondi, etc.), category quick selection chips, and curated featured rentals.
- **Search & Filters**: Real-time searching, category selection, minimum bedrooms, audience targeting (Family vs. Corporate), and dynamic price sliders.
- **Property Details**: Clean visual specs (beds, baths, size), verified badges, deep links to contact landlords via WhatsApp, and custom in-app inquiry submissions.
- **Local Database Persistence**: Powered by **Room (SQLite)** for holding property indexes, storing saved favorites, and keeping track of submitted inquiries offline.
- **Aesthetic Brand Style**: Customized styling implementing RentNin's dark navy (`#0C2340`) and emerald green (`#00A651`) brand identity.

## Tech Stack & Architecture

- **Language**: Kotlin 1.9.22
- **Framework**: Jetpack Compose (Material 3)
- **State Management**: MVVM Architecture (`RentViewModel` with `MutableStateFlow` and reactive data collection)
- **Data Persistence**: Room Database (KSP)
- **Image Loading**: Coil Compose with remote Unsplash content cache
- **Build System**: Gradle (Kotlin DSL)
