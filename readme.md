Habit It App
Empowering you to build better habits through technology.

📜 Overview
Habit It is a cutting-edge habit tracker built with Flutter and adhering to clean architecture principles. This app offers a streamlined experience for setting, tracking, and achieving your habit goals while providing insightful analytics to support your self-improvement journey.

🎯 Key Highlights:

Local Authentication: Biometric or PIN security.
Progress Analytics: Visual habit streaks and trends.
Offline Accessibility: Track habits anywhere, anytime.
User Personalization: Manage profiles and customize habit descriptions.

📂 Google Drive (APK Download)
👉 [Download the app](https://drive.google.com/file/d/1ETv7WnpfP4klRQCV9S2rRqwsDX-WJTKY/view?usp=drive_link)

🚀 Getting Started
Prerequisites
[Install Android Studio](https://developer.android.com/studio)

[Flutter Installation Guide.](https://docs.flutter.dev/get-started/install)

Steps to Run Habit It
1.Clone the repository:
    bash
    git clone (https://github.com/HASAN3149/habit-it-app)

2.Open the project in Android Studio.
Run the following command to fetch dependencies:
    bash
    flutter pub get  

4.Connect a physical device or configure an emulator in Android Studio. 

5.Enable USB debugging (for physical devices):
    *Go to Developer Options in device settings.
    *Enable USB Debugging.
6.Run the app:
    bash
    flutter run  

🏗️ Project Structure
plaintext
Copy code
├── android/           # Android app configuration  
├── assets/            # App resources (images, fonts, etc.)  
├── ios/               # iOS app configuration  
├── lib/               # Dart source code  
│   ├── config/        # App-level configurations  
│   ├── core/          # Core utilities and logic  
│   ├── data/          # Data management and repositories  
│   ├── features/      # Feature-specific modules  
│   ├── app.dart       # Main app setup  
│   ├── injection_container.dart  # Dependency injection setup  
│   └── main.dart      # App entry point  
├── test/              # Test cases  
└── pubspec.yaml       # Dependency management 

✨ Features
Flexible Habit Types: Track daily, weekly, or custom habits.

Visual Progress Monitoring: Charts and statistics to analyze habits.

Secure User Profiles: Authentication with biometrics or PIN.

Custom Descriptions: Add notes for clarity.

Dark Mode: Eye-friendly viewing at night.

Offline Mode: Access and track habits without internet.

🛠️ Technologies Used
#Get It: Dependency injection.

#Clean Architecture: Ensures scalability and maintainability.

#Local Authentication: For data security.

#Shared Preferences: Efficient local storage.

#Localization: Multi-language support.

#AppBar Calendar & Month Picker: Enhanced UI/UX.



🌟 Contribute
We welcome contributions! To get started:
#Fork the repository.
    1.Create a new branch: git checkout -b feature-branch. 

    2.Commit your changes: git commit -m "Add new feature".

    3.Push the branch: git push origin feature-branch.

    4.Submit a pull request.


📝 License
This project is licensed under the MIT License.

🚀 Start building better habits today with Habit It!