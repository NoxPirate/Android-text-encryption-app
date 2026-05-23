# Android Text Encryption App

This project is an Android application designed to provide users with tools for encrypting and hashing text. It implements several cryptographic algorithms, offering both encryption capabilities and hashing methods to secure text data.

## Features

* **Encryption Algorithms**: The app supports multiple classic and modern encryption algorithms, including:
* AES (Advanced Encryption Standard)


* DES (Data Encryption Standard)


* Caesar Cipher


* PlayFair Cipher


* Vigenere Cipher




* **Hashing**: Includes functionality for data hashing.


* **User-Friendly Interface**: Features a splash screen, a main activity for navigation, and dedicated fragments for different encryption and hashing operations.



## Project Structure

The project is organized following standard Android development conventions:

* **`app/src/main/java/Encryption/Algorithms/`**: Contains the core logic for the various encryption algorithms.


* **`app/src/main/java/Hash/`**: Contains the logic for hashing operations.


* **`app/src/main/java/Main/`**: Houses the main application activities (`MainActivity`, `SplashActivity`) and interface fragments.


* **`app/src/main/res/`**: Contains application resources, including:
* **`layout/`**: XML files defining the app's user interface.


* **`anim/`**: Animation resources for UI transitions.


* **`drawable/` & `mipmap/**`: Image assets, icons, and shape definitions.


* **`values/`**: Configuration files for strings, colors, and styles.





## Getting Started

1. Clone this repository to your local development environment.
2. Open the project in Android Studio.
3. Ensure the Android SDK and required Gradle build tools are configured as specified in the `build.gradle` and `gradle.properties` files.


4. Build and run the app on an Android emulator or a physical device.
