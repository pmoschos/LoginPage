# Login Page

## Project Overview
LoginDemoAppCF4 is an Android application demonstrating basic login functionality. This README focuses on the `MainActivity` class, which manages user authentication.

## Technologies & Tools

![Android](https://img.shields.io/badge/-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Android Studio](https://img.shields.io/badge/-Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)

## Installation
To set up this project:
1. Clone the repository to your local machine.
2. Open the project in Android Studio or your preferred IDE.
3. Build the project to resolve any dependencies.

## Usage
Run the app on an emulator or physical device. Enter username and password credentials, and click the login button to authenticate.

## Code Explanation
`MainActivity` extends `AppCompatActivity` and is responsible for user interactions.
- **UI Components:**
  - `EditText` for username (`usernameET`) and password (`passwordET`).
  - `Button` for login (`loginBtn`).
  - `TextView` for questions (`questionTV`) and registration (`registerTV`).
- The `onCreate` method sets up the UI layout and initializes components.
- The login button has an `OnClickListener` for handling authentication logic.

## Features
- Basic user authentication.
- Input validation for username and password.
- Navigation to `SecondActivity` upon successful login.

## Screenshots

### Login Screen
![image](https://github.com/pmoschos/LoginPage/assets/133533759/8897414b-d605-4f64-9cf5-21e26d39f319)


### Welcome Screen
![image](https://github.com/pmoschos/LoginPage/assets/133533759/91f171c2-224b-43d8-8557-45744b417acf)

## Contributions
Contributors are welcome. Please fork the repository and submit pull requests for any proposed changes.

## Contact Information
[pmoschos@aueb.gr]
