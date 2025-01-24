# Blockhouse AuthFlow

## Description
`blockhouse-authflow` is a basic React Native app that implements authentication screens for login and signup. It includes form validation for email format and password matching. The app uses Redux (or Context API) for state management and React Navigation for screen transitions.

This repository also includes a CI/CD setup using GitHub Actions, which automates linting, testing, and builds for both Android and iOS platforms.

## Features
- **Login Screen**: Email and password fields with validation.
- **Signup Screen**: Email, password, and confirm password fields with validation.
- **State Management**: Using Redux (or Context API) for managing authentication state.
- **Navigation**: React Navigation for navigating between the login and signup screens.
- **CI/CD Pipeline**:
  - Runs linting and basic tests on push events.
  - Automatically generates builds for Android and iOS on specific branches.
  
## Installation

### Prerequisites
Before running the app, make sure you have the following installed:

- Node.js
- React Native CLI
- Android Studio (for Android builds)
- Xcode (for iOS builds, macOS only)

### Steps to Run the App Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blockhouse-authflow.git
