# Payment App

This mobile app features a navigation system that utilizes Stack Navigation and Bottom Tabs Navigation to provide an intuitive user experience. Additionally, the app includes a theme switching feature that allows users to toggle between light and dark modes.

## Navigation

The app uses the following navigation components:

Stack Navigation: A stack-based navigation system that allows users to navigate between screens by pushing and popping screens from a stack. This is used for navigating between individual screens within the app.
Bottom Tabs Navigation: A tab-based navigation system that provides quick access to main sections of the app. This is used for navigating between main categories of the app.
Theme Switching

The app includes a theme switching feature that allows users to toggle between light and dark modes. This feature is implemented using a Switch component that updates the app's theme in real-time.

Implementation

The navigation system is implemented using the following components:

Stack.Navigator: A component that manages the stack of screens and provides navigation functionality.
Stack.Screen: A component that represents an individual screen within the stack.
BottomTab.Navigator: A component that manages the bottom tabs and provides navigation functionality.
BottomTab.Screen: A component that represents an individual tab within the bottom tabs.
The theme switching feature is implemented using the following components:

Switch: A component that allows users to toggle between light and dark modes.
ThemeContext: A context that stores the current theme and provides a way to update the theme.
How it works

The app uses the Stack Navigation system to navigate between individual screens.
The app uses the Bottom Tabs Navigation system to navigate between main categories of the app.
The theme switching feature is implemented using a Switch component that updates the app's theme in real-time.
When the Switch is toggled, the app's theme is updated, and the screens are re-rendered with the new theme.
## Screenshots

### LIGHT MODE 💡🔆
<img width="410" alt="Screenshot 2024-06-26 at 19 52 01" src="https://github.com/Kofidell4545/rn-assignment5-11014724/assets/151035682/1e3b94d5-01c7-446d-9f9e-eabaea3258e7">
<img width="410" alt="Screenshot 2024-06-26 at 19 52 11" src="https://github.com/Kofidell4545/rn-assignment5-11014724/assets/151035682/181b6a08-732b-4fc5-860d-60722ed18131">

### DARK MODE ⚫️

<img width="410" alt="Screenshot 2024-06-26 at 19 52 39" src="https://github.com/Kofidell4545/rn-assignment5-11014724/assets/151035682/1a4e2a8c-16e3-4a2d-9015-b54edbd3ae1d">

<img width="410" alt="Screenshot 2024-06-26 at 19 52 50" src="https://github.com/Kofidell4545/rn-assignment5-11014724/assets/151035682/12c5288a-d5ae-4099-8a8b-5917b78bef20">



Technical Details

React Native: The app is built using React Native, a framework for building cross-platform mobile apps.
Navigation: The app uses the react-navigation library to implement the navigation system.
Theme Switching: The app uses the react-native-switch library to implement the theme switching feature.
Getting Started

To get started with the app, simply clone the repository and run the following commands:

npm install
npx react-native run-ios (for iOS)
npx react-native run-android (for Android)
Contributing

Contributions are welcome! If you'd like to contribute to the app, please fork the repository and submit a pull request.

License

The app is licensed under the MIT License. See the LICENSE file for details.
