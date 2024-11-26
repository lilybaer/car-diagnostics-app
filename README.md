# *Car Diagnostics App*
## Overview
The Car Diagnostics App is a mobile application designed to help users identify and resolve vehicle issues based on symptoms they experience. The app allows users to input symptoms such as sight, smell, feel, sound, or issues where the car won’t start. Based on their selection, users are directed to a list of possible solutions submitted by other users. Users can also contribute their own solutions, which can be upvoted or downvoted within the app.

## Features
Symptom Selection: Users can choose from symptoms like "Sight", "Smell", "Feel", "Sound", or "Won't Start" to narrow down their issue.

Solution Lists: Each symptom selection brings the user to a list of possible solutions submitted by other users.

Upvote/Downvote System: Users can interact with solutions by voting them up or down.

User Contributions: Users can submit their own solutions and solutions that are approved by the app’s moderation system can be posted.

Comment Section: Each solution will have a comment section where users can ask questions, share thoughts, and engage with other contributors.

User Profiles: Users can customize their profile, view their past contributions, and manage their profile information.

Customizable Text Size and Dark Mode: Users can adjust text size and toggle dark mode to enhance readability and comfort.

## Technologies Used
iOS Development (Xcode, Swift): The app was developed using Swift in Xcode.

Firebase: Used for storing user data, solution submissions, comments, user profiles, and upvote/downvote counts.

Comments and User Profiles: Implemented using Firestore database to allow users to manage their comments, solutions, and profile information.

Custom Components (e.g., Comment Section): Developed reusable SwiftUI components for dynamic and responsive UI elements.

Dark Mode and Text Size Settings: Managed using app settings and user preferences stored in UserDefaults.
