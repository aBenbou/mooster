# Mooster
Mooster is a mobile application developed using Flutter, aimed at optimizing livestock management. This application enables owners and veterinarians to monitor and manage the health of their cattle in real-time, leveraging IoT devices (ESP8236) for temperature monitoring and health alerts.

## Features

- **Livestock Monitoring**: Access comprehensive profiles for each cow, detailing health status and checkup history.
- **Health Alerts**: Receive automatic notifications when a cow's health is at risk.
- **Veterinary Tools**: Log consultations, track medications, and monitor pregnancy status.
- **Admin Dashboard**: Manage user accounts and oversee the health of cattle across multiple farms.
- **IoT Integration**: Connects with ESP8236 temperature sensors for real-time health tracking of cows.

## User Roles

- **Admin**: Manages the system and oversees user accounts.
- **Owner**: Responsible for farm management and cattle health monitoring.
- **Veterinarian**: Monitors cow health, documents consultations, and updates health statuses.

## Getting Started

To run the project locally, you will need Flutter installed. For installation instructions, follow the official [Flutter documentation](https://flutter.dev/docs/get-started/install).

### Prerequisites

- Flutter SDK
- Firebase Account (Firestore for data management)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/abenbou/mooster
   cd mooster


2. **Install Dependencies**:
   Run the following command to install all necessary Flutter packages:
      flutter pub get
   
3. **Set Up Firebase**:
   Follow the official Firebase setup instructions for Flutter.
   Add google-services.json (for Android) and GoogleService-Info.plist (for iOS) to the respective platforms.

4. **Run the App**:
   To launch the app on your device or emulator, use the command:
      flutter run
