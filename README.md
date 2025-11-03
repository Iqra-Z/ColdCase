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
┣ 📂 ui
┃ ┣ MainActivity.kt 
┃ ┣ LoginActivity.kt 
┃ ┣ SignupActivity.kt
┃ ┣ MapActivity.kt 
┃ ┗ ProfileActivity.kt 
┣ 📂 data 
┃ ┣ FirebaseHelper.kt 
┃ ┗ CaseModel.kt 
┣ 📂 resources 
┃ ┣ layout/ 
┃ ┣ drawable/ 
┃ ┗ values/ 
┗ AndroidManifest.xml

## Protoype Progress


















