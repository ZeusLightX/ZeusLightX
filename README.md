# Ubika

Ubika – Real-Time Lost & Found Community App

Ubika is a real-time Android application that connects people to report, locate, and recover lost or stolen items and people/pets.
Built with a focus on usability, community trust, and efficient geolocation, it allows users to post alerts, view nearby reports on a map, and communicate through categorized alerts — all in one sleek and responsive interface.

🌟 Features
🔐 Authentication

Firebase Authentication for secure login and registration.

Users can log in with either email or username.

🧭 Interactive Map

Displays real-time alerts on Google Maps with category-based custom markers.

Users can tap markers to open detailed views with descriptions, photos, and actions.

Nearby alerts are shown by default to keep the experience localized and relevant.

🗂️ Alert System

Create, edit, and delete personal alerts with a title, description, category, and image.

Categories include: Lost Item, ID, Mobile, Car, Pet, and more.

Alerts are stored in Firebase Firestore and synced instantly across users.

🖼️ Media Handling

Image uploads stored in Firebase Storage with compressed transfer for performance.

Smooth image rendering via Glide library.

👤 User Profile

Custom avatars selectable from a pre-loaded grid.

Dynamic XP & Rank system: users earn experience points for creating alerts.

Novato (1) → Reportero (2) → Rastreador (3) → Guardián (4)

Profile updates automatically synced with Firestore.

🔔 Push Notifications

Firebase Cloud Messaging (FCM) integration for instant updates when new alerts are posted.

🧱 UI & UX

Built entirely in Java with XML layouts following Material Design guidelines.

Smooth navigation using BottomNavigationView for Map, Alerts, and Profile sections.

Consistent color palette and responsive layouts for multiple screen sizes.

🧰 Tech Stack
Client (Android App):	Java, XML, AndroidX, Material Components
Backend & Cloud:	Firebase Firestore, Firebase Authentication, Firebase Storage, Cloud Messaging
Maps Integration:	Google Maps SDK for Android
Image Loading:	Glide
Notifications:	FCM
Build Tools:	Gradle
Version Control:	Git & GitHub

⚙️ Architecture

MVVM-inspired structure with clear separation of UI, data, and logic.

Firestore rules configured for data security (users can only modify their own alerts).

Real-time synchronization between users for alerts and profiles.

📈 Future Enhancements

Commenting system under each alert.

Private messaging between users.

Optional AI-powered image recognition for automatic item categorization.

Multi-language support (Spanish, English).

👨‍💻 Developer

Mohamed Ghanem Hassan
Software Engineer | Full-Stack & Android Developer
📍 Spain
🔗 [LinkedIn](https://www.linkedin.com/in/mohamed-ghanem-hassan-4a39101a1/)

