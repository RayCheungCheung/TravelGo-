# TravelGo-
# TravelGo! 🌍✈️

**From virtual maps to real meetings - A social exploration app designed for travelers and adventure buddies**

[![Flutter](https://img.shields.io/badge/Flutter-3.16-blue.svg)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.0-blue.svg)](https://dart.dev)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Web-lightgrey)

<p align="center">
  <img src="https://img.shields.io/badge/Map_Social-Innovative-red" alt="Map Social">
  <img src="https://img.shields.io/badge/Real-time_Location-Accurate-blue" alt="Real-time Location">
  <img src="https://img.shields.io/badge/Scratch_Map-Fun-green" alt="Scratch Map">
  <img src="https://img.shields.io/badge/Cross_Platform-iOS/Android/Web-purple" alt="Cross Platform">
</p>

<p align="center">
  <img src="assets/screenshots/app_demo.gif" alt="TravelGo! Demo" width="300">
  <br>
  <em>Experience the future of social travel exploration</em>
</p>

## 🎯 Vision

TravelGo! is a revolutionary social travel exploration app that perfectly blends the magic of real-world encounters with the desire to document travel footprints. We believe true travel isn't just about reaching destinations, but about who you share the journey with.

> **From "Where are you?" to "Let's go together!"**

## ✨ Core Features

### 🗺️ Smart Scratch Map
- **Auto-Recording**: Go places, scratch maps! Automatically records every corner you explore
- **Visual Progress**: Color heatmaps show your exploration density and frequency
- **Achievement System**: Unlock exploration achievements, compete with friends on coverage
- **Travel Memories**: Every scratched area holds photos and stories

### 👥 Real-time Social Exploration
- **Live Friend Locations**: See where your friends are in real-time, with battery levels and status
- **Group Exploration**: Start adventures together with the innovative "BUMP!" feature
- **Travel Timeline**: Collaborative memory albums organized by location and time
- **Shared Playlists**: Integrated Spotify/Apple Music for synchronized travel vibes

### 🎮 Gamified Travel Experience
- **Exploration Leaderboard**: Compete with friends on who discovers more
- **City Unlocking**: Collect virtual stamps for each new city visited
- **Challenge Mode**: Complete location-based challenges for rewards
- **Travel Stats**: Comprehensive analytics of your exploration journey

### 🔒 Privacy First Design
- **Ghost Mode**: Temporarily hide your location when needed
- **Granular Controls**: Choose who sees what, when, and where
- **Travel-Only Sharing**: Set visibility only during trips
- **Auto-Cleanup**: Old location data automatically expires

## 🚀 Quick Start

### Prerequisites
- Flutter SDK (>= 3.16.0)
- Dart (>= 3.0.0)
- iOS 13+ or Android 8.0+

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/travelgo.git
cd travelgo

# Install dependencies
flutter pub get

# Run the app
flutter run
```

### Configuration

1. **Get API Keys**:
   - [Mapbox](https://www.mapbox.com/) (for maps)
   - [Supabase](https://supabase.com/) (for backend - optional)
   - [Firebase](https://firebase.google.com/) (alternative backend)

2. **Configure Environment**:
```bash
# Copy environment template
cp .env.example .env

# Add your API keys to .env
MAPBOX_ACCESS_TOKEN=your_token_here
SUPABASE_URL=your_url_here
SUPABASE_ANON_KEY=your_key_here
```

## 🏗️ Architecture

```
lib/
├── main.dart                 # App entry point
├── models/                   # Data models
│   ├── user_model.dart
│   ├── travel_model.dart
│   └── scratch_map_model.dart
├── providers/               # State management
│   ├── user_provider.dart
│   ├── map_provider.dart
│   └── scratch_map_provider.dart
├── screens/                 # App screens
│   ├── home_screen.dart
│   ├── scratch_map_screen.dart
│   ├── explore_screen.dart
│   └── profile_screen.dart
├── widgets/                 # Reusable components
│   ├── friend_list_widget.dart
│   ├── explore_button.dart
│   ├── scratch_map_stats.dart
│   └── memory_card.dart
└── services/               # External services
    ├── location_service.dart
    ├── map_service.dart
    └── database_service.dart
```

## 🛠️ Tech Stack

| Technology | Purpose | Why We Chose It |
|------------|---------|-----------------|
| **Flutter** | Cross-platform UI | Single codebase for iOS, Android, Web |
| **Dart** | Programming language | Optimized for Flutter, fast development |
| **Provider** | State management | Simple yet powerful, perfect for this scale |
| **Flutter Map** | Map rendering | Open-source, customizable, performant |
| **Supabase** | Backend/Real-time DB | Open-source Firebase alternative |
| **GetX** | Navigation & DI | Optional for complex routing |
| **Google Fonts** | Typography | Beautiful, free fonts |

## 📱 Screenshots

<div align="center">
  <table>
    <tr>
      <td><img src="assets/screenshots/home.png" alt="Home Screen" width="200"></td>
      <td><img src="assets/screenshots/scratch_map.png" alt="Scratch Map" width="200"></td>
      <td><img src="assets/screenshots/explore.png" alt="Explore" width="200"></td>
    </tr>
    <tr>
      <td align="center">Home Screen</td>
      <td align="center">Scratch Map</td>
      <td align="center">Explore</td>
    </tr>
  </table>
</div>

## 🎨 UI/UX Design Principles

1. **Travel-Centric**: Every design decision considers the traveler's context
2. **Minimalist Maps**: Clean, uncluttered maps with essential information
3. **Social First**: Easy friend interactions with minimal taps
4. **Offline Ready**: Core functionality works without internet
5. **Accessibility**: High contrast, large touch targets, screen reader support

## 🔧 Development

### Running Tests
```bash
# Unit tests
flutter test

# Integration tests
flutter test integration_test/

# Run with coverage
flutter test --coverage
```

### Building Releases
```bash
# Build Android APK
flutter build apk --release

# Build Android App Bundle
flutter build appbundle --release

# Build iOS
flutter build ios --release

# Build Web
flutter build web --release
```

### Code Quality
```bash
# Format code
flutter format .

# Analyze code
flutter analyze

# Generate documentation
dart doc .
```

## 📈 Project Status

| Feature | Status | Version |
|---------|--------|---------|
| Core Map Interface | ✅ Complete | v1.0 |
| Scratch Map System | ✅ Complete | v1.0 |
| Real-time Locations | 🟡 In Progress | v1.1 |
| Offline Maps | 🟡 Planned | v1.2 |
| AR Exploration | 🔴 Future | v2.0 |
| Web Version | 🟡 In Progress | v1.1 |

## 🤝 Contributing

We love contributions! Here's how you can help:

1. **Fork** the repository
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Development Guidelines
- Follow [Flutter Style Guide](https://dart.dev/guides/language/effective-dart/style)
- Write tests for new features
- Update documentation accordingly
- Use meaningful commit messages

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by Zenly's social location features
- Built with amazing open-source libraries
- Icons from [Material Design Icons](https://fonts.google.com/icons)
- Maps powered by [OpenStreetMap](https://www.openstreetmap.org/)

## 📞 Support

- 📧 Email: support@travelgo.app
- 🐛 [Issue Tracker](https://github.com/yourusername/travelgo/issues)
- 💬 [Discord Community](https://discord.gg/travelgo)
- 📱 [App Store](https://apps.apple.com/app/travelgo) (Coming Soon)
- 📱 [Google Play](https://play.google.com/store/apps/details?id=app.travelgo) (Coming Soon)

## 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/travelgo&type=Date)](https://star-history.com/#yourusername/travelgo&Date)

---

<p align="center">
  Made with ❤️ for travelers around the world
  <br>
  <em>Because every journey is better when shared</em>
</p>

<div align="center">
  
  **Download Now** → [iOS](https://apps.apple.com/app/travelgo) | [Android](https://play.google.com/store/apps/details?id=app.travelgo)
  
  <sub>Available soon on both platforms</sub>
</div>
