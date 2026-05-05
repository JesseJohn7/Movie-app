# Movie App

![Stars](https://img.shields.io/github/stars/JesseJohn7/Movie-app) ![Forks](https://img.shields.io/github/forks/JesseJohn7/Movie-app) ![Last Commit](https://img.shields.io/github/last-commit/JesseJohn7/Movie-app)

## Description

The Movie App is a Web application built with NextJs and typescript that helps people get access too movies 

## Installation

To get started with the Movie App, clone the repository and install the necessary dependencies. You can do this using the following commands:

```bash
git clone https://github.com/JesseJohn7/Movie-app.git
cd Movie-app
npm install
```

## Usage

Once the setup is complete, you can start the app using any of the following commands depending on your target platform:

```bash
npm run start         # Starts the development server
npm run android       # Runs the app on Android
npm run ios           # Runs the app on iOS
npm run web           # Runs the app in a web browser
npm run lint          # Runs the linter to check for code quality
```

The initial screen displays a welcome message. The main component responsible for rendering this view can be found in `app/index.tsx`:

```javascript
import { Text, View } from "react-native";

export default function Index() {
  return (
    <View style={{ flex: 1, justifyContent: "center", alignItems: "center" }}>
      <Text>Welcome</Text>
    </View>
  );
}
```

## Tech Stack

- **Front-end Framework**: React Native
- **Routing**: Expo Router
- **Styles**: Tailwind CSS via NativeWind
- **Navigation**: React Navigation
- **Development Environment**: Expo

## Directory Structure

- `app/`: Contains application layout and main components
- `assets/`: Holds images and icons used in the application
- `babel.config.js`: Configuration for Babel
- `package.json`: Contains project metadata and dependencies

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss enhancements and features.

## License

This project does not have a specified license. Please consider this when contributing or using the project.