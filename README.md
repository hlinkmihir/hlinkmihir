# KikIO Project Overview

## Table of Contents
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Details](#folder-details)
---

## Project Structure
This project follows the **MVC (Model-View-Controller)** pattern for clear separation of concerns and maintainable code.

```
Root
├── Base/
├── APIManager/
├── Resources/
├── ThirdParty/
├── Model/
├── Utility/
├── Controller/
└── View/
    └── Xibs/
        ├── Authentication/
        ├── Home/
        ├── RecentTask/
        ├── AddTask/
        └── Profile/
```

---

## Requirements
- iOS 13.0+
- Xcode 14.0+
- Swift 5+

---

## Installation
1. Clone the repository:
   ```bash
   git clone url
   cd your-repo-folder
   ```
2. Install dependencies (if any, e.g., using CocoaPods).
   ```bash
   pod install   # using CocoaPods
   ```
3. Open the `.xcworkspace` file in Xcode:
   ```bash
   open .xcworkspace
   ```

---

## Usage
1. Build the project in Xcode:
   - Select the correct scheme and device/emulator.
   - Click **Run** (⌘ + R).
2. Ensure all required APIs are configured correctly in the `APIManager` folder.
3. You can customize resources under `Resources/` (e.g., assets, localized strings).

---

## Folder Details
### **Base/**
Contains AppDelegate and SceneDelegate classes.

### **APIManager/**
Manages API calls, networking logic, and data fetching from remote servers. also contain the encryption algorithm configuration.

### **Resources/**
Holds assets, images, localization files, and other static resources.

### **ThirdParty/**
Contains third-party libraries or modules.

### **Model/**
Defines the data structures and models used within the app.

### **Utility/**
Includes helper functions, extensions, and utilities used across multiple components.

### **Controller/**
Contains view controllers managing the user interface and interactions.

### **View/Xibs/**
Holds all XIB files for different UI components:
- **Authentication**: Login, signup, and authentication-related screens.
- **Home**: Main dashboard or home screen.
- **RecentTask**: Displays recently added tasks or activity logs.
- **AddTask**: Screen for adding new tasks.
- **Profile**: User profile and settings screen.
