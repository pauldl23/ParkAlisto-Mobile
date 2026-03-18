# 🅿️ ParkAlisto Mobile

A modern, beautifully designed **smart parking reservation app** built with Flutter. ParkAlisto helps users find, compare, and book parking spots in real time — featuring an Apple-inspired **Liquid Glass UI** design system with frosted glass effects and dynamic animations.

---

## ✨ Features

- **Smart Parking Search** — Browse nearby parking locations with real-time availability
- **Interactive Spot Selection** — Visual parking grid to choose your preferred spot
- **Booking Management** — View, track, and manage all your reservations
- **Interactive Map** — Explore parking locations on an integrated map view
- **Onboarding Flow** — Smooth first-time user experience
- **Account Management** — User profile and settings

## 🎨 Design System

ParkAlisto uses an **Apple Liquid Glass UI** design language featuring:

- Frosted glass containers with blur effects and translucency
- Dynamic mesh gradient backgrounds
- Smooth micro-animations and transitions
- Light theme with brand green (`#2E7D32`) accent color
- Google Fonts typography (Outfit)

## 🏗️ Project Structure

```
lib/
├── main.dart                  # App entry point
├── theme.dart                 # Global theme & design tokens
├── models/
│   ├── booking.dart           # Booking data model
│   ├── parking_location.dart  # Parking location model
│   └── parking_spot.dart      # Individual spot model
├── screens/
│   ├── home_screen.dart       # Main dashboard with search
│   ├── choose_spot_screen.dart# Spot selection grid
│   ├── booking_success_screen.dart
│   ├── my_bookings_screen.dart
│   ├── map_screen.dart        # Interactive parking map
│   ├── account_screen.dart    # User profile & settings
│   ├── onboarding_screen.dart # First-time user flow
│   └── main_shell.dart        # Bottom navigation shell
├── services/
│   ├── app_state.dart         # Provider state management
│   └── mock_data.dart         # Sample data for development
└── widgets/
    ├── glass_container.dart    # Frosted glass card widget
    ├── glass_button.dart       # Glassmorphic button
    ├── dynamic_mesh_background.dart # Animated gradient bg
    └── car_placeholder.dart    # Vehicle illustration widget
```

## 🛠️ Tech Stack

| Layer              | Technology                  |
| ------------------ | --------------------------- |
| **Framework**      | Flutter (Dart SDK ^3.10.7)  |
| **State Management** | Provider                  |
| **Backend**        | Supabase                    |
| **Typography**     | Google Fonts (Outfit)       |
| **Icons**          | Cupertino Icons             |
| **Platforms**      | iOS, Android, Web, macOS, Linux, Windows |

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (^3.10.7)
- Dart SDK (bundled with Flutter)
- Xcode (for iOS) / Android Studio (for Android)

### Installation

```bash
# Clone the repository
git clone https://github.com/yanellebryan/ParkAlisto-Mobile.git
cd ParkAlisto-Mobile

# Install dependencies
flutter pub get

# Run the app
flutter run
```

## 📄 License

This project is private and not published to pub.dev.

---

<p align="center">
  Built with 💚 using Flutter
</p>
