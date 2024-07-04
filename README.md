# Instagram Clone App

## Overview
This project is a clone of Instagram developed using Flutter. It includes features similar to Instagram, such as user authentication, a responsive layout for mobile and web platforms, and the ability to view different screen layouts based on the user's login status.

## Features
- **User Authentication:** Users can log in using Firebase Authentication.
- **Responsive Layout:** Adaptable layout for both mobile and web platforms.
- **Firebase Integration:** Utilizes Firebase for backend services including authentication and storage.
- **User Interface:** Modern and clean UI similar to Instagram's interface.

## Technologies Used
- Flutter
- Dart
- Firebase (Authentication, Firestore, Storage)
- `provider` for state management
- `flutter_svg` for handling SVG images
- `image_picker` for selecting images

## Getting Started

### Prerequisites
- Flutter SDK installed
- Dart SDK installed
- Firebase project set up

### Installation
1. **Clone the repository:**
```bash
git clone https://github.com/your-username/instagram-clone-flutter.git
```

2. **Navigate to the project directory:**
```bash
cd instagram_clone_flutter
```
3. **Install dependencies:**
```bash
flutter pub get
```
## Firebase Setup
1. **For Web:**

- Replace the Firebase configuration in the main.dart file with your Firebase web app configuration.

2. **For Mobile:**

- Ensure you have added the google-services.json file (for Android) or GoogleService-Info.plist (for iOS) to your project as per Firebase setup instructions.

## Running the App
1. **Run the application:**
```bash
flutter run
```
## Usage Instructions
1. **Authentication:**

- Users can log in using their credentials.
- Upon successful login, users will be redirected to the main app layout based on their device type (mobile or web).

2. **Responsive Layout:**

- The app will automatically adjust its layout based on the screen size and platform.

## Author
- Akash R
