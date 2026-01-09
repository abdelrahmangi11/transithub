# 🚚 TransitHub

**TransitHub** is a peer-to-peer shipping and goods transfer mobile application built with **Flutter** and **Dart**.  
The app connects travelers with people who need to ship items along the same route, making deliveries faster, cheaper, and more flexible.

---

## 📌 Project Idea

TransitHub enables users to:
- Create trips with a specific route and time.
- Allow other users to request shipping goods along that trip.
- Communicate directly through in-app chat to coordinate delivery details.

This peer-to-peer model reduces shipping costs and utilizes existing travel routes efficiently.

---

## ✨ Features

- 🔐 **User Authentication**
  - Secure login and registration.
  - User profiles with basic information.

- 🧳 **Trip Creation**
  - Create a trip with source, destination, date, and time.
  - View available trips posted by other users.

- 📦 **Shipping Requests**
  - Request a traveler to ship goods along their route.
  - Accept or reject shipping requests.

- 💬 **Real-time Chat**
  - In-app chat between sender and traveler.
  - Discuss item details, pickup, and delivery arrangements.

- 🔗 **API Integration**
  - Consume RESTful APIs for trips, users, and requests.
  - Real-time data synchronization.

---

## 🛠️ Tech Stack

- **Flutter** – Cross-platform mobile development
- **Dart** – Programming language
- **Firebase**
  - Authentication
  - Cloud Firestore / Realtime Database
  - Cloud Messaging (optional)
- **REST APIs** – Backend communication



## 🚀 Getting Started

### Prerequisites
- Flutter SDK
- Dart
- Android Studio / VS Code
- Firebase project setup

### Installation

```bash
git clone https://github.com/your-username/transithub.git
cd transithub
flutter pub get
flutter run
