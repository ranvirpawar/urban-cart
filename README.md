# 🛒 Urban Cart 

![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white&style=flat) ![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white&style=flat) ![BLoC](https://img.shields.io/badge/BLoC-02569B?logo=bloc&logoColor=white&style=flat) ![Version](https://img.shields.io/badge/version-1.0.0-blue)

## 📱 Overview

The **Grocery App** is a mobile application built with [Flutter](https://flutter.dev/), utilizing the [BLoC](https://bloclibrary.dev/#/) (Business Logic Component) state management to provide a seamless and reactive user experience for managing grocery lists, shopping carts, and orders.

## 🎯 Features

- 🛍️ **Browse Products:** Explore a variety of grocery items.
- 🔍 **Search Functionality:** Find products quickly with a powerful search.
- 🛒 **Shopping Cart:** Add and manage items in your cart.
- 📋 **Order History:** Track your past orders.
- 🌐 **API Integration:** Fetch real-time data from a backend server.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- [Android Studio](https://developer.android.com/studio) or [Visual Studio Code](https://code.visualstudio.com/) with Flutter and Dart plugins.

## Key Components
BLoC (Business Logic Component): Manages state and business logic.
Models: Data structures for the application.
Repositories: Handle data fetching and persistence.
Screens: UI components for different pages.
Widgets: Reusable UI components.

## 🛠️ Technical Details
#### State Management with BLoC
The app uses the BLoC pattern to manage state efficiently. BLoC separates business logic from the UI, ensuring a clean architecture and better testability.

**Event**: User actions that trigger state changes.
**State**: Represents the UI state.
**BLoC**: Handles events and updates the state accordingly.
