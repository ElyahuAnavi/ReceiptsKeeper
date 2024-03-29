
# <img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/f188a221-ae00-439a-999a-51c6e73087d3" width="50"> ReceiptsKeeper 

## Table of Contents
- [Screenshots](#screenshots-)
- [Overview](#overview-)
- [Features](#features-)
- [Installation](#installation-️)
- [Usage](#usage-)
- [Technical Details](#technical-details-)
- [Dependencies](#dependencies-)
- [Contributing](#contributing-)
- [License](#license-)

## Screenshots 📸

<table>
  <tr>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/b23c71cb-1490-42d8-bbfe-8e2f5bd8e368" width="250" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/5f2fda27-c998-4951-a3da-fa603a6d5a8a" width="250" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/46aa742f-b712-4c5c-a24c-23d585ad9ac9" width="250" /></td>
  </tr>
  <tr>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/e0f6f202-becb-4814-be2d-ad3bb2906348" width="250" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/f072d54a-5d39-4474-85ca-2a07d6a97c7b" width="250" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/f82ebf45-440f-4fa6-8df8-659c16e0d70a" width="250" /></td>
  </tr>
   <tr>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/c3134f0e-118e-44fa-83fe-64a8a5d51a0e" width="250" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/32d2b5be-0f5b-4f38-b981-1b1c6f71decf" width="250" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/59655b86-91e2-4304-98b8-a95951fa7342" width="250" /></td>
  </tr>
   <tr>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/0061b71b-6106-4b26-93cf-30de1df88fd1" width="250" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/2c04126a-91b6-4bd8-90ee-657ded2aa0fa" width="250" /></td>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/33f709c9-50de-439f-95af-447f600c9615" width="250" /></td>
  </tr>
   <tr>
    <td><img src="https://github.com/ElyahuAnavi/ReceiptsKeeper/assets/137146370/550637c5-88ad-4049-ba84-1807e74bb664" width="250" /></td>
  </tr>
</table>




## Overview 📱
ReceiptsKeeper is an innovative Android application designed for the savvy user who wants to streamline their appointment and receipt management. Developed using the Android API, Java, and Firebase, this app offers a seamless way to organize and access your financial documents related to appointments.

## Features 🌟
- **Receipt Storage:** 🧾 Save your receipts for each appointment, ensuring you never lose track of your expenses.
- **Calendar Integration:** 📅 A comprehensive calendar system to track your appointments with ease.
- **Monthly Reports:** 📊 Generate and view detailed monthly reports of your appointments and associated receipts.
- **Report Sharing:** 📤 Share your monthly reports via WhatsApp, making it easy to communicate and keep records.
- **User Authentication:** 🔐 Keep your data secure with Firebase authentication, ensuring only you can access your information.
- **Cloud Storage:** ☁️ Leverage Firebase's cloud storage for safe and accessible receipt storage.

## Installation 🛠️
To get started with ReceiptsKeeper, clone the repository to your local machine and import the project into Android Studio. Ensure your environment is set up with the latest Android SDK and your Firebase project credentials are configured.

## Usage 📲
1. **Start the App:** Open ReceiptsKeeper on your device, and log in or register.
2. **Appointment Management:** Easily add and manage your appointments using the in-built calendar.
3. **Save Receipts:** Attach receipts to your appointments to keep everything organized.
4. **View Reports:** Access monthly reports to review your appointment expenses.
5. **Share Reports:** Utilize the share feature to send your reports via WhatsApp.

## Technical Details 🔧
- **Target SDK:** The app targets API level 33, compatible with a wide range of Android devices.
- **Minimum SDK Requirement:** Supports devices with SDK version 27 and above.
- **Dependencies:** Includes libraries for Firebase services and modern UI components to enhance the user experience.

## Dependencies 📦

Here's a list of dependencies used in ReceiptsKeeper:

- **Testing Frameworks:**
  - `junit:junit:4.13.2` - A unit testing framework for Java applications.
  - `androidx.test.ext:junit:1.1.5` - Additional testing support for JUnit in Android.
  - `androidx.test.espresso:espresso-core:3.5.1` - An instrumentation-based API to write UI tests.

- **Android Support and UI:**
  - `androidx.appcompat:appcompat:1.6.1` - Support library for app bar and UI elements on older Android versions.
  - `com.google.android.material:material:1.9.0` - Material Design components for modern UI design.
  - `androidx.constraintlayout:constraintlayout:2.1.4` - A powerful layout manager for flexible UI design.

- **Firebase:**
  - `com.google.firebase:firebase-auth:22.0.0` - Firebase authentication for user management.
  - `com.google.firebase:firebase-firestore:24.6.1` - Firestore for cloud storage and syncing of app data.
  - `com.google.firebase:firebase-storage:20.2.0` - Firebase storage for file management.
  - `com.google.firebase:firebase-database:20.2.2` - Firebase Realtime Database for data syncing.

- **Third-party Libraries:**
  - `com.google.android.gms:play-services-auth:20.5.0` - Google Sign-In integration.
  - `com.airbnb.android:lottie:3.7.1` - Library for rendering After Effects animations.
  - `com.squareup.picasso:picasso:2.71828` - Image loading and caching library.
  - `joda-time:joda-time:2.10.10` - Library for date and time manipulation.
  - `de.hdodenhof:circleimageview:3.1.0` - Circular ImageView implementation.
  - `com.github.razir.progressbutton:progressbutton:2.1.0` - Customizable progress button library.
  - `com.prolificinteractive:material-calendarview:1.4.3` - Custom calendar view.
  - `com.itextpdf:itextg:5.5.10` - Library for creating PDF documents.
  - `com.github.f0ris.sweetalert:library:1.6.2` - Library for custom alert dialogs.

These dependencies are integral to the functionality and aesthetics of ReceiptsKeeper, providing a robust and user-friendly experience.

## Contributing 🤝
We welcome contributions to ReceiptsKeeper! Whether it's enhancing functionality, fixing bugs, or improving documentation, feel free to fork the repository and submit your pull requests.

## License 📜
ReceiptsKeeper is available under the [MIT License](https://opensource.org/licenses/MIT), allowing free use, modification, and distribution of the software.

---

