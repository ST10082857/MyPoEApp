# MyPoEApp - Fitness & Workout Tracking App

<div align="center">
  <img src="app/src/main/res/drawable/app_logo.xml" width="120" height="120" alt="MyPoEApp Logo">
</div>

## Project Description
MyPoEApp is a comprehensive fitness tracking application developed as part of my Portfolio of Evidence (POE). The app helps users maintain their fitness journey by providing features for workout tracking, nutrition monitoring, and goal setting, all while implementing modern Android development practices and secure authentication methods.

## Features

### Authentication & Security
- Google Sign-In Integration
- Biometric Authentication (Fingerprint/Face Recognition)
- Secure Email/Password Registration
- Firebase Authentication Backend

### Workout Features
- Real-time GPS Workout Tracking
- Multiple Workout Types:
  - Running
  - Walking
  - Cycling
  - Strength Training
- Detailed Statistics:
  - Distance
  - Pace
  - Calories Burned
  - Route Mapping

### Nutrition Tracking
- Daily Meal Logging
- Nutritional Information Database
- Macro Tracking (Protein, Carbs, Fats)
- Calorie Monitoring
- Custom Meal Creation

### Goal Management
- Customizable Fitness Goals
- Progress Tracking
- Achievement System
- Regular Progress Updates

## Technical Implementation

### Architecture & Design
- MVVM Architecture Pattern
- Material Design 3 UI Components
- Repository Pattern for Data Management
- Clean Architecture Principles

### Technologies Used
- Kotlin Programming Language
- Android Jetpack Components
- Firebase Services
- Room Database
- Google Maps Integration
- Biometric Authentication

## Setup & Installation

### Prerequisites
- Android Studio Hedgehog | 2023.1.1 or newer
- JDK 11 or higher
- Android SDK with minimum API 27
- Google Play Services
- Firebase Account

### Installation Steps
1. Clone the repository
```bash
git clone https://github.com/ST10082857/MyPoEApp.git
```

2. Open project in Android Studio

3. Configure Firebase:
   - Add your `google-services.json`
   - Enable Authentication services
   - Set up Firestore Database

4. Build and run the application

## Project Structure
```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/mypoeapp/
│   │   │   ├── api/          # API and network calls
│   │   │   ├── data/         # Data models and database
│   │   │   ├── ui/           # UI components
│   │   │   ├── services/     # Background services
│   │   │   └── utils/        # Utility classes
│   │   └── res/              # Resources
│   └── test/                 # Unit tests
└── build.gradle.kts          # Project configuration
```

## Testing
- Unit Tests for ViewModels and Repository
- UI Tests for Critical User Flows
- Integration Tests for Database Operations

## Future Enhancements
- Social Features & Sharing
- Advanced Analytics Dashboard
- Workout Plan Recommendations
- Integration with Wearable Devices

## Author
- **Name:** Mushfeeq Hartnick
- **Student Number:** ST10082857

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Android Development Team
- Firebase Documentation
- Material Design Guidelines
