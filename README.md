Flutter Task Manager with Back4App Authentication
This is a simple task manager application built with Flutter and uses Back4App for user authentication.

Features
User Authentication: Sign up, log in, and log out functionality using Back4App.
Task Management: Users can create, edit, and delete tasks.
Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

Prerequisites
Flutter SDK
Dart SDK
An IDE (like Android Studio or VS Code)
A Back4App account
Setup
Clone the repository to your local machine.
Open the project with your IDE.
Go to lib/main.dart and replace 'YOUR_APP_ID_HERE', 'YOUR_CLIENT_KEY_HERE', and 'https://parseapi.back4app.com' with your actual Back4App Application ID, Client Key, and Server URL.
Run flutter pub get to fetch the project dependencies.
Start your emulator or connect your mobile device.
Run flutter run to start the application.
Usage
Sign Up: New users can create an account by providing a username, email, and password.
Log In: Existing users can log in by providing their username and password.
Create Task: After logging in, users can create a new task by entering the task details.
Edit Task: Users can edit an existing task by updating the task details.
Delete Task: Users can delete an existing task.
Log Out: Users can log out from their account.
Built With
Flutter - The UI framework used
Dart - The language used
Back4App - The backend used for user authentication
