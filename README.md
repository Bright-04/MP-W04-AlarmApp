# Alarm App

## Overview
A simple yet functional alarm clock application developed for Android using Kotlin.
This app was created as part of a Mobile Programming coursework at HCMUTE.

## Features
- User-friendly interface with a time picker
- Real-time display of selected alarm time
- 24-hour time format support
- Sets alarms using Android's built-in alarm functionality
- Custom alarm message: "Wake up for class!"
- Error handling for devices that don't support alarm functionality

## Implementation Details

### Technology Stack
- Kotlin programming language
- Android SDK

### Key Components
- **TimePicker**: Allows users to select the desired alarm time
- **Button**: Triggers alarm creation
- **TextView**: Displays the currently selected time
- **Intent System**: Uses Android's `AlarmClock.ACTION_SET_ALARM` intent to create alarms

### Code Structure
The app consists of a single `MainActivity` that:
1. Initializes UI components in the `onCreate()` method
2. Updates the displayed time whenever the user interacts with the TimePicker
3. Creates and sends an alarm intent when the "Set Alarm" button is pressed
4. Provides appropriate user feedback via Toast messages

## How to Use
1. Launch the app
2. Use the time picker to select your desired alarm time
3. The selected time will display in real-time above the picker
4. Press the "Set Alarm" button
5. The system alarm app will open (if EXTRA_SKIP_UI is set to false)
6. Confirm your alarm settings if prompted
7. A toast message will confirm the alarm has been set

## Requirements
- Android device or emulator
- Minimum SDK version: *(Not specified in provided code)*
- A system app capable of handling alarm intents

## Setup Instructions
1. Clone the repository
2. Open the project in Android Studio
3. Build and run the application on your device or emulator

## Permissions
This app requires no special permissions to operate.

## Future Improvements
- Add ability to set multiple alarms
- Include options for recurring alarms
- Add custom sounds and vibration patterns
- Implement a snooze feature
- Add support for alarm label customization

---
*This project was developed for educational purposes as part of the Mobile Programming course at HCMUTE.*

