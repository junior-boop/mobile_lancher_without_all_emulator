# PROPOSITION: NATIVE ANDROID AND IOS APP LAUNCHER WITHOUT EMULATOR
### Introduction

As mobile developers, we are all familiar with Android and iOS emulators. They allow us to test our applications in a virtual environment, but they can be resource-intensive and slow down our development process.

### Problem

Traditional emulators launch a complete environment (operating system, system applications, and services). This requires a large amount of RAM, CPU, and storage space, which can slow down laptops and desktops that are less powerful.

### Solution

**Reduced resource usage:** I propose developing an application that embeds everything needed to launch an Android or iOS application, without the need for a full emulator. This application would work like a native application using the machine's resources and not dedicated resources like emulators, but it would open like current emulators, a separate window with the appearance of a phone.

### Advantages

**Reduced resource usage:** The application would only launch the components necessary to run the application under development, which would significantly reduce the consumption of RAM, CPU, and storage space.
**Better performance:** The application being lighter, it would run faster and more smoothly, even on less powerful machines. Since it only uses the resources necessary for the launcher and the application under development.
### Features

**The application would include the following features:**

- Launching Android and iOS applications
- Configuring resolution and pixel density
- External window with the appearance of a phone
- Status bar and navigation bar (visual only)
- Notification management and display

### Non-features

- Control panel
- Navigation bar functionality (Android and iOS)