# Superheroes App 🦸‍♂️🦸‍♀️

An Android application that showcases a list of powerful superheroes, their descriptions, and their legendary images. This project was built to practice **Jetpack Compose**, **Material 3 Design**, and custom theming.

## ✨ Features
- **Scrollable Hero List**: Uses `LazyColumn` for efficient list rendering.
- **Material 3 UI**: Implements the latest Material Design components including `Scaffold`, `Card`, and `CenterAlignedTopAppBar`.
- **Custom Theming**: 
  - **Color**: Custom light and dark color schemes.
  - **Typography**: Uses the **Cabin** font family (Regular & Bold).
  - **Shapes**: Custom rounded corner configurations.
- **Dynamic Adaptability**: Supports both Light and Dark modes.
- **Accessibility**: Includes content descriptions for images to support screen readers.

## 📸 Screenshots
![Screenshot_20260309_145602_One UI Home](https://github.com/user-attachments/assets/1008894a-eeb6-45bd-995d-929d8c9a30d4)
![Screenshot_20260309_142303_Superheroes](https://github.com/user-attachments/assets/d848f4da-1dfd-4b87-b833-3ff6601013cf)



## 🛠 Tech Stack
- **Language**: [Kotlin](https://kotlinlang.org/)
- **UI Framework**: [Jetpack Compose](https://developer.android.com/jetpack/compose)
- **Design System**: [Material 3](https://m3.material.io/)
- **Architecture**: Clean separation of UI (Composables) and Data (Model/Repository).

## 🚀 Getting Started

### Prerequisites
- Android Studio
- Android SDK 34+

### Installation
1. Clone the repository:
2. Open the project in **Android Studio**.
3. Let Gradle sync and download dependencies.
4. (Optional) Ensure you have added the required images to `app/src/main/res/drawable`.
5. Run the app on an emulator or physical device.

## 📂 Project Structure
app/src/main/java/com/example/superhero/

├── model/
│   ├── Hero.kt              # Data class defining the Hero object
│   └── HeroesRepository.kt  # Object holding the superhero data set
│
├── ui/theme/
│   ├── Color.kt             # Custom color definitions (Material 3 palette)
│   ├── Shape.kt             # Corner radius configurations
│   ├── Theme.kt             # SuperheroesTheme setup (Light/Dark logic)
│   └── Type.kt              # Custom typography using Cabin fonts
│
├── HeroesScreen.kt          # Composable functions for hero list and hero items
└── MainActivity.kt          # App entry point and Scaffold structure

