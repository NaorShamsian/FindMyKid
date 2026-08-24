# FindMyKid 📍

FindMyKid is an Android application built in **Java** that allows parents to connect with their children, track their location in real time, and receive important alerts and emergency updates.

The application uses **Firebase** for authentication, real-time data synchronization, and push notifications, while **osmdroid** is used for map visualization and location tracking.

---

## 🚀 Main Features

* **Real-Time Location Tracking** – Parents can view their child's current location and receive continuous location updates.
* **Parent-Child Connection** – Securely connect parent and child accounts using QR codes.
* **Child Management** – Parents can manage connected children and access their current status.
* **Emergency Alerts** – Children can trigger emergency events and notify their parent.
* **Push Notifications** – Real-time alerts are delivered using Firebase Cloud Messaging.
* **Authentication** – User registration and login are handled using Firebase Authentication.
* **Live Data Synchronization** – Child location and account data are synchronized through Firebase Realtime Database.
* **Interactive Maps** – Child locations are displayed using osmdroid maps.

---

## 🛠️ Technology Stack

* **Language:** Java
* **Platform:** Android
* **Authentication:** Firebase Authentication
* **Database:** Firebase Realtime Database
* **Push Notifications:** Firebase Cloud Messaging (FCM)
* **Maps:** osmdroid
* **Location Services:** Google Play Services Location
* **QR Codes:** ZXing
* **UI:** AndroidX, Material Design, RecyclerView

---

## 📱 Application Flow

### Parent

1. Create or log in to a parent account.
2. Connect a child using a generated QR code.
3. View and manage connected children.
4. Track a child's location on the map.
5. Receive alerts and emergency notifications.

### Child

1. Log in to the child's account.
2. Connect to a parent account.
3. Share location updates with the parent.
4. Trigger an emergency alert when needed.

---

## 🔗 Parent-Child Connection

The application uses **ZXing** to create and scan QR codes.

The QR-based connection allows a parent and child account to be linked without requiring users to manually enter identifiers.

Once connected, the relationship is stored in Firebase and can be used for location tracking and alerts.

---

## 📍 Location Tracking

The application continuously retrieves the child's device location using Android location services.

Location information is synchronized through **Firebase Realtime Database**, allowing the parent's device to receive updated coordinates.

The location is displayed on an **osmdroid** map so the parent can easily view the child's current position.

---

## 🔔 Notifications & Emergency System

FindMyKid uses **Firebase Cloud Messaging (FCM)** to support push notifications.

The emergency functionality allows important events to be sent to the parent in real time, providing a fast way to react when assistance is needed.

---

## 🔐 Authentication

User accounts are managed with **Firebase Authentication**.

The application separates parent and child users and maintains the relationships between their accounts through Firebase.

---

## ⚙️ Requirements

* Android Studio
* Android SDK 24 or higher
* Java 11
* Firebase project
* Internet connection
* Location permissions enabled on the Android device

---

## ▶️ Getting Started

1. Clone the repository:

```bash
git clone https://github.com/NaorShamsian/FindMyKid.git
```

2. Open the project in **Android Studio**.

3. Configure your Firebase project and add the required `google-services.json` file.

4. Sync the Gradle dependencies.

5. Run the application on an Android device or emulator.

For real-time location functionality, testing on a physical Android device is recommended.

---

## 📦 Main Dependencies

```text
Firebase Authentication
Firebase Realtime Database
Firebase Cloud Messaging
osmdroid
Google Play Services Location
ZXing
AndroidX RecyclerView
Material Components
```

---

## 🎯 Project Purpose

FindMyKid was developed to demonstrate the implementation of a real-world Android application involving:

* Real-time data synchronization
* Location services
* Mobile authentication
* Push notifications
* QR-based device/account pairing
* Map integration
* Android background and permission-based functionality
