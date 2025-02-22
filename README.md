# Expo CLI: Android Emulator Crash on Specific Function Call

This repository demonstrates a bug encountered while using the Expo CLI with an Android emulator. The app functions correctly on a physical device but crashes the emulator when a specific function is called.

## Bug Description

The app launches on the Android emulator without issues. However, when the `myFunction` function (see `bug.js`) is triggered, the emulator becomes unresponsive and eventually crashes.  The error logs provide minimal information.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install` to install the necessary dependencies.
3. Run `expo start`.  
4. Launch the app on the Android emulator.
5. Trigger the `myFunction` function within the app.  
6. Observe the emulator crash.

## Solution

The solution involves identifying and addressing the issue within the application code which causes the emulator to crash. This will often be specific to the application and requires debugging and code analysis for resolution.

## Note

This bug was highly specific to the emulator; no issues were encountered on a physical device.  The root cause likely involves differences in resource management or specific system calls.