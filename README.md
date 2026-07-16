# Hi there 👋

Hi! I'm **Fadhlan**, a mobile developer specializing in **Flutter** with 3+ years of experience shipping production apps to the Play Store and App Store. I build with **Clean Architecture** and the **BLoC** pattern, and I'm expanding into backend development.

## 📱 Live Apps

* **[SFA/Visitqu](https://play.google.com/store/apps/details?id=com.sisapp.salesforce&hl=en-ID)**
  A sales force automation app for planning visits and collecting data.
* **BizOps** — [Google Play](https://play.google.com/store/apps/details?id=com.divistant.ex_mobile.ex_mobile&hl=id) · [App Store](https://apps.apple.com/id/app/bizops/id6733236612)
  A business operations support app that streamlines internal workflows.
* **BizOps Chat** — [Google Play](https://play.google.com/store/apps/details?id=com.divistant.bizops.chat) · [App Store](https://apps.apple.com/id/app/bizops-chat/id6754753212)
  A companion chat app for BizOps, shipped to the Play Store and App Store.

## 🛠️ Demo Projects

### Demo Note App

A code showcase demonstrating **Clean Architecture** and coding style, rather than UI slicing.

#### Features

* Create, edit, and delete notes
* Clean and intuitive user interface
* Efficient state management using the **BLoC** pattern
* Adheres to Clean Architecture principles

#### Tech Stack

* **Flutter & Dart** – Core framework and language
* **flutter_bloc** – State management
* **flutter_screenutil** – Responsive UI scaling
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
