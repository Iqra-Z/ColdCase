# ColdCase
The goal of the interactive smartphone application Cold Case AR is to combine community involvement, augmented reality (AR), maps integration, and true crime storytelling.  Through an immersive and instructive experience, the app enables users to inspect evidence, investigate both real and hypothetical cold cases, and participate properly in debates.

## Features
- Authentication: Firebase Authentication is used in this secure sign-up and login system.
- Interactive Map: Use Google Maps integration to view the locations of crimes that have been solved and those that have not.
- Case Explorer: Look through local or international cold cases with thorough case summaries.
- User Roles: Facilitates appropriate discourse by supporting moderator, guest, and user roles.
- Profile Management: Enables users to manage accounts and update personal data.
- Media Support: Pictures, videos, and audio narrations to visualize the evidence.
- View crime scenes that have been reconstructed in augmented reality (AR) mode (coming soon).

## Project Motivation
Through active inquiry and learning, the app seeks to replace the passive consumption of actual crime information.  Users can "become detectives" and participate in important conversations about community awareness and real-world justice by fusing gamification with mobile technology.

## System Overview
- Front-end: XML, Kotlin/Java, Android Studio
- Back-end: Firebase (storage, real-time database, and authentication)
- APIs: ARCore (planned) and Google Maps SDK
- Media Tools: Integrated captioned video and audio players
- Version control with GitHub and Git

## Architecture
<img width="212" height="510" alt="image" src="https://github.com/user-attachments/assets/5319e807-b3ba-4f53-b088-4531f50240f2" />

## Protoype Progress
✅ Completed
- Login & Signup
- Firebase Authentication
- Profile Page

🚧 In Progress
- Case List & Map Integration
- AR Integration

🚧 Planned
- Discussion Threads

## Tech Stack
- Language: Java / Kotlin
- IDE: Android Studio
- Database: Firebase Realtime Database
- Map API: Google Maps SDK
- Authentication: Firebase Auth
- Design Tools: Canva, Figma (mockups)
- Version Control: Git + GitHub

## Installation
1. Clone the repository
git clone https://github.com/your-username/ColdCaseAR.git
cd ColdCaseAR
2. Open in Android Studio
File > Open > ColdCaseAR
3. Add your Firebase configuration file (google-services.json) to the /app folder.
4. Add your Google Maps API key in AndroidManifest.xml:
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_API_KEY_HERE"/>
5. Build and run on an emulator or physical device.

## Future Enhancements
- Include support for Augmented Reality (AR) to create realistic crime scene visuals.
- Establish discussion boards with tools for moderation.
- Introduce themes for dark mode and offline caching.
- Increase the number of actual cold instances in the dataset

## Team Members
- Iqra Zahid         100824901
- Navdeep Virdi      100827233
- Mahnoor Jamal      100822030
- Riya Rajesh        100869701
- Sehar Ahmed        100808249

