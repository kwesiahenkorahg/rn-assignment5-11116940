# rn-assignment5-11116940

# Kwesi Ahenkorah Gyamenah

## Description

This React Native application, built using Expo, features multiple screens including Home, Settings, My Cards, and Statistics. The app supports light and dark themes, which users can toggle from the Settings screen. The design closely matches the provided UI mockup, ensuring a polished and consistent user experience.

## Getting Started

### Prerequisites

- Node.js
- Expo CLI

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/kwesiahenkorahg/rn-assignment5-11116940.git
   ```

2. Navigate to the project directory:
   ```sh
   cd rn-assignment5-11116940/MyProject
   ```

3. Install the dependencies:
   ```sh
   npm install
   ```

4. Install required Expo dependencies:
   ```sh
   npx expo install @react-navigation/native @react-navigation/bottom-tabs react-native-paper react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
   ```

### Running the App

1. Start the Expo development server:
   ```sh
   npm start
   ```

2. Use the Expo Go app on your mobile device to scan the QR code and run the app.

## Features

- **Home Screen**: Displays a welcome message, a card section, and a transaction list.
- **Settings Screen**: Allows users to switch between light and dark themes.
- **My Cards Screen**: Displays user's credit cards.
- **Statistics Screen**: Shows user's transaction statistics.
- **Dark Mode**: Users can toggle between light and dark themes.

## Screenshots

### Light Mode

#### Home Screen
![photo_10_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/d64cbd29-82b8-4408-9bba-ee911238fe4e)
![photo_2_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/6cdd048a-cb52-4697-9319-5d36bd15f26c)


#### Settings Screen
![photo_4_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/9cfd84d3-9fdd-4762-a328-960859dfd63f)


#### My Cards Screen
![photo_8_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/380fc90b-c793-41ce-908b-b145ad0a4561)


#### Statistics Screen
![photo_7_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/5ec6e4c7-8998-4216-95c4-30e714805a7a)


### Dark Mode

#### Home Screen
![photo_3_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/969f407b-f433-4b88-8bc6-6d3ae765d608)
![photo_1_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/72f4bbf9-a8eb-4e47-b833-7ae86ce7f40f)


#### Settings Screen
![photo_6_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/3471d403-50dc-4eca-a7c0-3c1a94c66851)


#### My Cards Screen
![photo_9_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/eeb91204-49ae-4512-954c-6f521419c586)


#### Statistics Screen
![photo_5_2024-06-26_21-23-30](https://github.com/kwesiahenkorahg/rn-assignment5-11116940/assets/170183906/677e085f-1634-4267-ab68-7630db78aabb)

## Development

### Dependencies

This project uses the following major dependencies:

- `@react-navigation/native`
- `@react-navigation/bottom-tabs`
- `react-native-paper`
- `react-native-gesture-handler`
- `react-native-reanimated`
- `react-native-screens`
- `react-native-safe-area-context`
- `@react-native-community/masked-view`

### Folder Structure

```
/rn-assignment5-11116940
├── MyProject
│   ├── .expo                    # Expo project files
│   ├── assets                   # All images and other static assets
│   ├── node_modules             # Node.js modules
│   ├── screens                  # Screen components for navigation
│   ├── .gitignore               # Git ignore file
│   ├── App.js                   # Main entry point for the app
│   ├── app.json                 # Expo app configuration
│   ├── babel.config.js          # Babel configuration
│   ├── package-lock.json        # Lockfile for npm
│   ├── package.json             # Project dependencies and scripts
│   ├── theme-context.js         # Theme context for dark/light mode
├── README.md                    # Project README file
```

### Theme Management

The theme context (`theme-context.js`) handles the light and dark mode toggling. It uses React's context API to provide theme data and toggle functionality throughout the application. The header and tab bar colors are adjusted based on the selected theme.
