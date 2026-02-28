Allergy Scanner App – React Native

# Allergy Scanner App – React Native 

[![React Native](https://img.shields.io/badge/React%20Native-Expo-blue?logo=react)](https://reactnative.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-lightgrey?logo=apple&logoColor=white)]()
[![API Connected](https://img.shields.io/badge/API-Barcode%20%26%20Allergy%20Checker-orange)]()

## About this project

This is my **first React Native application**, created to learn how to:

-  Work with external APIs
-  Understand React Native using **Expo**
-  Integrate barcode scanning
-  Automatically check for allergens in scanned products

###  How does it work?

1. You select your allergies (e.g., gluten, lactose, peanuts, etc.)
2. Scan the **barcode** of a product
3. The app fetches the **ingredients using an API**
4. If the product contains an ingredient you're allergic to → you’ll get an alert 

##  Quick Start (with Expo)

You only need **Node.js** to get started!

###  Requirements

- [Node.js](https://nodejs.org/) (v18 or higher)
- Expo CLI  
  Install with:
  ```bash
  npm install -g expo-cli
  ```
- Expo Go app on your phone (iOS or Android)

###  Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/RDeBont/allergy-scanner.git
   cd allergy-scanner
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Install additional Expo libraries**
   Used for the barcode scanner:
   ```bash
   npx expo install expo-barcode-scanner
   ```

4. **Start the project**
   ```bash
   npx expo start
   ```

5. **Scan the QR code**  
   Use the Expo Go app on your phone to run the app immediately.

##  Technologies Used

| Technology           | Description                                       |
|----------------------|---------------------------------------------------|
| React Native (Expo)  | For building the app                              |
| Expo Barcode Scanner | For scanning product barcodes                     |
| Fetch                | For fetching data from an API                     |
| React Navigation     | (Optional) for navigating between screens         |

##  What I Learned

-  How to build an app using React Native (via Expo)
-  How to use an external API to fetch and process data
-  How to implement a barcode scanner in an app
-  How to use logic to detect allergens


