# ArchiveApp - Firebase-Based Note-Taking Application

An Android note-taking application utilizing Firebase for authentication and Firestore for data storage.

## Table of Contents
- [Background](#background)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Background
ArchiveApp is a simple and efficient note-taking application for Android. It enables users to create, edit, and store notes securely using Firebase services.

## Features
- **User Authentication**: Secure login and registration using Firebase Authentication.
- **Create Notes**: Users can create and save notes in Firestore.
- **Edit Notes**: Modify existing notes easily.
- **View Notes**: Access stored notes in a list format.
- **Forgot Password**: Reset password functionality via email.
- **Firestore Database Integration**: Notes are stored and retrieved using Firestore.
- **RecyclerView for Notes**: Displays notes in an organized grid layout.

## Technologies Used
- **Android Development**: Java
- **Firebase Services**:
  - Authentication
  - Firestore Database
- **UI Components**: RecyclerView, EditText, FloatingActionButton
- **Version Control**: Git/GitHub

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/shwetamadhale/ArchiveApp.git
   ```
2. Open the project in Android Studio.
3. Ensure Firebase dependencies are added to `build.gradle`.
4. Connect Firebase to your project.
5. Run the app on an emulator or device.

## Usage
1. **Sign up/Login** using email authentication.
2. **Create new notes** by entering a title and content.
3. **Edit notes** by selecting them from the list.
4. **Reset password** using the Forgot Password option.
5. **View all saved notes** in a structured format.

## Project Structure
```
ArchiveApp/
│── app/src/main/java/com/example/archive/
│   ├── MainActivity.java        # Handles user login
│   ├── CreateNote.java          # Handles note creation
│   ├── EditNoteActivity.java    # Handles note editing
│   ├── NoteDetails.java         # Displays note details
│   ├── FirebaseModel.java       # Data model for notes
│   ├── ForgotPassword.java      # Manages password reset
│   ├── NotesActivity.java       # Displays list of notes
│── app/src/main/res/layout/     # UI layouts
│── app/build.gradle             # Project dependencies
```

## Contributing
Contributions are welcome! Feel free to submit pull requests or open issues.

## License
This project is licensed under the MIT License.

