<div align="center">

<img src="https://d117h1jjiq768j.cloudfront.net/images/default-source/blogs/2019/2019-10/the-react-native-sdk-for-kinvey-is-now-available_870_450.png?sfvrsn=296e1008_0" height="175" alt="React Native">

# Prana.io

Cross-platform mobile application for travel and geolocation documentation

</div>

<p align="center">
  <a href="https://github.com/facebook/react-native/blob/HEAD/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="React Native is released under the MIT license." />
  </a>
  <a href="https://www.npmjs.org/package/react-native">
    <img src="https://img.shields.io/npm/v/react-native?color=brightgreen&label=npm%20package" alt="Current npm package version." />
  </a>
  <a href="https://reactnative.dev/docs/contributing">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs welcome!" />
  </a>
</p>

---

## Downloading the App

This app is currently in beta for testing. To download version 0.1.1 to your mobile device for review:

- ### iOS

  - A free download of the app is available via [Apple TestFlight](https://developer.apple.com/testflight/): to join the Prana.io beta
  - Step 1, download [TestFlight](https://testflight.apple.com/) from the App Store to your mobile device
  - Step 2, visit the public link on your iOS device to download: https://testflight.apple.com/join/JDZDY79Y

- ### Android
  - _Awaiting review from Google Play_

---

## Beta App Information

Cross-platform mobile application for travel & geolocation documentation. Create and store a list of defined locations to the device with an associated image and description. Click the saved location to reveal the location details screen. Interactive map screen for viewing or selecting location. Requires permissions for native camera, photo library, and geolocation features.

---

## Project Details

- Developed with [React Native](https://reactnative.dev/) (0.64.3) and the [Expo](https://expo.dev/) SDK (43.0.0)
- [Google Maps Platform](https://developers.google.com/maps) for geolocation
- Allows the user to create and store a list of defined locations with an associated image and description
- Home screen provides a list of user created locations with a clickable details screen
- Interactive map screen for viewing or selecting locations
- Persists data via [SQLite](https://www.sqlite.org/index.html)
- Automated address retrieval via reverse-geolocation
- Utilizes native camera, photo library, and map functionality
- [Redux](https://redux.js.org/) to manage location state
- Button icons by [ionicons](https://ionic.io/ionicons) via [react-native-vector-icons](https://www.npmjs.com/package/react-native-vector-icons)
- Icons made by [Freepik](https://www.freepik.com) from www.flaticon.com
- This application utilizes a [.env](https://www.npmjs.com/package/react-native-dotenv) file to host environment variables, for utilization include:
  - GOOGLE_API_KEY={Your_Google_Maps_API_Key_Here}

---

## Getting Started

- To install the Expo CLI

  ```bash
  npm install --global expo-cli
  ```

- To install dependencies, navigate to the 'src' directory and execute in the terminal:

  ```bash
  npm install
  ```

- To run the development server:

  ```bash
  npm start
  ```

---

## About React Native

React Native brings [**React**'s][r] declarative UI framework to iOS and Android. With React Native, you use native UI controls and have full access to the native platform.

[r]: https://reactjs.org/
[p]: https://reactnative.dev/docs/out-of-tree-platforms
[e]: https://github.com/facebook/react-native/blob/HEAD/ECOSYSTEM.md

## Contents

- [Requirements](#-requirements)
- [Documentation](#-documentation)
- [License](#-license)

---

## 📋 Requirements

React Native apps may target iOS 11.0 and Android 5.0 (API 21) or newer. You may use Windows, macOS, or Linux as your development operating system, though building and running iOS apps is limited to macOS. Tools like [Expo](https://expo.io) can be used to work around this.

---

## 📖 Documentation

The full documentation for React Native can be found on our [website][docs].

The React Native documentation discusses components, APIs, and topics that are specific to React Native. For further documentation on the React API that is shared between React Native and React DOM, refer to the [React documentation][r-docs].

The source for the React Native documentation and website is hosted on a separate repo, [**@facebook/react-native-website**][repo-website].

[docs]: https://reactnative.dev/docs/getting-started
[r-docs]: https://reactjs.org/docs/getting-started.html
[repo-website]: https://github.com/facebook/react-native-website

### [Open Source Roadmap][roadmap]

You can learn more about our vision for React Native in the [**Roadmap**][roadmap].

[roadmap]: https://github.com/facebook/react-native/wiki/Roadmap

---

## 📄 License

React Native is MIT licensed, as found in the [LICENSE][l] file.

React Native documentation is Creative Commons licensed, as found in the [LICENSE-docs][ld] file.

[l]: https://github.com/facebook/react-native/blob/HEAD/LICENSE
[ld]: https://github.com/facebook/react-native/blob/HEAD/LICENSE-docs
