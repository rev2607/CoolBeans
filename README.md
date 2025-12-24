# CoolBeans
> A learning-focused iOS app built with SwiftUI to explore caffeine and calorie tracking for coffee and tea drinks.

![Tech Stack](https://img.shields.io/badge/Tech-Swift|SwiftUI|iOS-blue)

## Overview
**CoolBeans** is a personal learning project where I explored building a multi-screen SwiftUI application around a simple, real-world use case: tracking caffeine and calorie intake from beverages.

The goal of this project was not to build a production-ready health app, but to practice:
- SwiftUI view composition
- Basic state management
- Data modeling
- Navigation and user interaction flows

## Features
- Browse a predefined menu of coffee and tea drinks
- View caffeine and calorie information per drink
- Customize drinks with size and add-ons
- Log drinks to a simple consumption history
- View a basic daily summary of intake

> Note: Features are intentionally scoped for learning purposes and do not aim to cover all real-world edge cases.

## Demo

[![Watch the video](https://github.com/rev2607/CoolBeans/blob/main/Assets.xcassets/AppIcon.appiconset/appstore1024.png)](https://github.com/rev2607/CoolBeans/assets/117919399/e51bff3d-8fee-4e6d-921a-de2fd78a77c2)

## Tech Stack
- **Language**: Swift
- **UI Framework**: SwiftUI
- **Core Frameworks**: Foundation
- **Tools**: Xcode, iOS Simulator, Git
- **Platform**: iOS
- **Architecture**: Simple MVVM-style separation using `ObservableObject`

## Getting Started

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/CoolBeans.git
   cd CoolBeans
   ```

2. Open in Xcode

   * Open `CoolBeans.xcodeproj`
   * Select a simulator or device
   * Build and run (⌘R)

### Requirements

* Xcode 12 or later
* iOS 14.0+

## Project Structure

```
CoolBeans/
├── CoolBeans/
│   ├── Assets.xcassets/          # App icons and images
│   ├── ContentView.swift         # Root view and entry point
│   ├── Drink.swift               # Core drink data model
│   ├── Menu.swift                # Static menu data handling
│   ├── MenuView.swift            # Drink selection UI
│   ├── CustomizeView.swift       # Drink customization screen
│   ├── History.swift             # Simple consumption history
│   ├── Serving.swift             # Serving size model
│   └── menu.json                 # Sample drink data
├── CoolBeans.xcodeproj/
└── README.md
```

## Technical Focus Areas

* SwiftUI view hierarchy and layout
* `@State` and `ObservableObject` for managing UI state
* Passing data between views
* Modeling domain data using Swift structs
* Building navigation flows using SwiftUI

## Limitations & Future Improvements

This project reflects my early-stage iOS learning and has several known limitations:

* Data persistence is minimal and not designed for long-term storage
* No user accounts or sync across devices
* No advanced analytics or visualizations
* UI and logic are tightly scoped for clarity rather than scale

Potential future improvements include better persistence, clearer separation of concerns, and more robust state management for larger feature sets.

## What I Learned

This project helped me understand how SwiftUI's declarative model works in practice and how state changes drive UI updates. Building multiple screens clarified how data flows through an app and where different responsibilities should live.

I also learned the importance of scoping features realistically and being clear about trade-offs when building learning projects. CoolBeans served as a foundation for strengthening my SwiftUI fundamentals before moving on to more complex iOS applications.
