# Flash Chat ⚡️

## Overview
This app was built based on LondonAppBrewery's Flutter Development Bootcamp. The app is a modern, real-time messaging app powered by Flutter and Firebase. It features user authentication and cloud-based messaging, offering a dynamic platform for users to sign up, log in, and engage in conversations with others. The app showcases the integration of Firebase Cloud Firestore for real-time message exchanges and Firebase Auth for secure user authentication, delivering a comprehensive chat experience.

## Features

- **User Authentication**: Utilizes Firebase Auth to manage user registration and sign-in, ensuring secure access to the app.
- **Real-Time Chat**: Leverages Firebase Cloud Firestore to enable real-time sending and receiving of messages, creating an interactive user experience.
- **Modern UI/UX**: Incorporates Flutter's customizable widgets to design a sleek and user-friendly interface.
- **Animations**: Enhances user interactions with smooth transitions and animations, utilizing Flutter's Hero widget and animation controllers.
- **Cloud-Based Data Storage**: Employs Firebase Cloud Firestore for efficient, scalable, and real-time data storage and retrieval.

![Finished App](https://github.com/londonappbrewery/Images/blob/master/flash_chat_flutter_demo.gif)

## Technology Stack

- **Flutter**: An open-source UI software development kit created by Google for building natively compiled applications for mobile, web, and desktop from a single codebase.
- **Firebase Cloud Firestore**: A flexible, scalable database for mobile, web, and server development from Firebase and Google Cloud.
- **Firebase Auth**: A service that can authenticate users using only client-side code. It supports social login providers like Google, Facebook, and Twitter, as well as email and password login; moreover, it includes a user management system.

By utilizing these technologies, Flash Chat offers a robust platform for users to communicate instantly, showcasing the power and flexibility of Flutter and Firebase in app development.
## How to Run the App

1. **Set up Flutter on your machine**: Ensure that you have Flutter installed on your machine. If not, follow the instructions on the [official Flutter website](https://flutter.dev/docs/get-started/install).

2. **Clone the repository**: Clone this repository to your local machine using `git clone https://github.com/yourusername/flash-chat-flutter.git`.

3. **Set up Firebase**:
    - Go to the [Firebase Console](https://console.firebase.google.com/) and create a new project.
    - Add an Android and/or iOS app to your Firebase project. Follow the setup instructions provided by Firebase.
    - For Android, download the `google-services.json` file and place it in the `android/app` directory.
    - For iOS, download the `GoogleService-Info.plist` file and place it in the `ios/Runner` directory.
    - Use the Firebase CLI to enable Firebase services like Firestore and Authentication for your project.

4. **Run the app**:
    - Open a terminal in the project directory and run `flutter pub get` to install all the dependencies.
    - Run `flutter run` to build and run the app on a connected device or emulator.

## Additional Notes

- Make sure to replace the Firebase project placeholders with your own Firebase project details in `google-services.json` and `GoogleService-Info.plist`.
- You might need to perform additional configuration steps for Firebase on iOS or Android, as mentioned in the Firebase setup guide.





