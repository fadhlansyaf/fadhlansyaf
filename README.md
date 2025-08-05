# Hi there 👋

Hi! I’m **Fadhlan**, a passionate mobile developer specializing in **Flutter**, dedicated to building high-quality mobile applications. Always eager to learn and expand my skills, including exploring other mobile platforms and languages such as Swift for iOS, Kotlin for Android, and Kotlin Multiplatform for shared codebases.

## 📱 Live Apps

* **[SFA/Visitqu](https://play.google.com/store/apps/details?id=com.sisapp.salesforce&hl=en-ID)**
  A sales force automation app for planning visits and collecting data.

* **[Ayoo Desa Juara!](https://play.google.com/store/apps/details?id=id.ayodesajuara.app&hl=en-ID)**
  A community development app that empowers villages with interactive features.

* **BizOps**
  Android: [Google Play](https://play.google.com/store/apps/details?id=com.divistant.ex_mobile.ex_mobile&hl=id)

  iOS: [App Store](https://apps.apple.com/id/app/bizops/id6733236612)

  A business operations support app that streamlines internal workflows.

## 🛠️ Demo Projects

### Demo Note App

A simple note-taking app code showcase demonstrating Clean Architecture and coding style, rather than UI slicing.

#### Features

* Create, edit, and delete notes
* Clean and intuitive user interface
* Efficient state management using the **BLoC** pattern
* Adheres to Clean Architecture principles

#### Tech Stack

* **Flutter & Dart** – Core framework and language
* **flutter\_bloc** – State management
* **flutter\_screenutil** – Responsive UI scaling
* **equatable** – Value equality
* **marquee** – Text scrolling animation

#### Architecture

```plaintext
lib/
├── core/
│   └── data_state.dart          # Base data state handling
├── data/
│   ├── datasources/             # Data sources implementation
│   ├── models/                  # Data models
│   └── repository/              # Repository implementations
├── domain/
│   ├── entity/                  # Business entities
│   ├── repository/              # Repository interfaces
│   └── usecase/                 # Use cases
├── presentation/
│   ├── bloc/                    # BLoC state management
│   └── screens/                 # UI screens
└── widgets/                     # Reusable UI components
    ├── custom_app_bar.dart
    ├── custom_button.dart
    ├── custom_scaffold.dart
    ├── custom_text_field.dart
    ├── error_section.dart
    ├── text_style/
    └── texts/
```
