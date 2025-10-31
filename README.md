# Mobile Inventory & Stock Management App

A comprehensive mobile application designed for efficient **inventory tracking** and **stock management**, featuring barcode scanning, real-time data synchronization, and analytics. A revamp of ExDaTrIM. 

## Features

* **Barcode Scanning:** Quickly add or update products using an integrated **Barcode Scanner** leveraging the device's camera.
* **Stock Management:** Track product quantities, manage batches, and maintain an organized inventory list/table.
* **Data Synchronization:** Real-time data sync using **Firebase** for secure, cross-device access and backup.
* **Analytics & Reporting:** View statistics and insights on stock levels, turnover, and product movement.
* **Multi-Language Support:** Localized interface with language selection options.
* **Product Information Lookup:** Integrate with external databases (like **Open Food Facts**, which was used here, but other databases is a OK) to automatically fetch product details.
* **Local Notifications:** Get alerts for low stock or other critical inventory events.

## Technology Stack

This project is built using:

* **React Native / Expo:** For cross-platform mobile development.
* **Firebase:** For backend services, including real-time database and potentially authentication.
* **JavaScript (ES6+)**
* **Expo Application Services (EAS):** For simplified building and deployment.

## Getting Started

### Prerequisites

* Node.js (LTS version)
* npm or Yarn
* Expo CLI (`npm install -g expo-cli`)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/razojhameas/SINOP.git
    cd my-sinop
    ```
2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```
3.  **Setup Firebase:**
    * Create a new project in the Firebase Console.
    * Update the configuration in `utils/firebase.js`.
4.  **Setup Environment Variables:**
    * Write an **`.env`** and fill in your keys (e.g., API keys, Firebase configuration details). 

### Running the App Locally

1.  **Start the Expo development server:**
    ```bash
    expo start
    ```
2.  **Run on a device or emulator:**
    * Scan the QR code with the **Expo Go** app on your phone.
    * Press `a` to run on an Android emulator or `i` to run on an iOS simulator (if set up).



# SINOP
<img src="assets/Icon.png" alt="SINOP App Icon" width="512"/>






