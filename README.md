# Safe Campus

Safe Campus is a Flutter mobile app concept for a campus emergency alert (SOS) system, built as a group project. The goal is to let students quickly raise an emergency alert from their phone and have it reach campus authorities in real time, with a separate admin side to receive and respond to those alerts.

This repository is in an early, work-in-progress stage: the project structure and screen files for the planned features are in place, but the core logic is not implemented yet.

## Planned Features

- Student registration and login
- One-tap SOS / emergency alert from the student's device
- Admin panel to view and respond to incoming alerts
- Role-based access: separate flows for students (users) and campus admins

## Current Status

- `login_screen.dart`, `register_screen.dart`, `user_screen.dart`, and `admin_screen.dart` exist as placeholder files under `lib/screens/`, not yet implemented
- `main.dart` still runs the default Flutter starter template and is not wired up to these screens yet

This is an active group project, so the structure above reflects the current checkpoint rather than the finished app.

## Tech Stack

- Flutter (Dart)

## Project Structure

```
safe_campus/
└── lib/
    ├── main.dart
    └── screens/
        ├── login_screen.dart
        ├── register_screen.dart
        ├── user_screen.dart
        └── admin_screen.dart
```

## Getting Started

### Prerequisites
- Flutter SDK installed

### Running the app

```bash
git clone https://github.com/Ashikur-Arman/Safe-Campus.git
cd Safe-Campus/safe_campus
flutter pub get
flutter run
```

## Team

This is a group project built collaboratively as part of a university course.

## License

Add a license here if you plan to open-source this project.
