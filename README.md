This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

## Step 3: Modifying your App

Now that you have successfully run the app, let's modify it.

1. Open `App.tsx` in your text editor of choice and edit some lines.
2. For **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Developer Menu** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (on Window and Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (on macOS)) to see your changes!

   For **iOS**: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes!

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.

install https://www.npmjs.com/package/react-native-haptic-feedback 

![image](https://github.com/jotalexvalencia/RollTheDice5/assets/10563766/ec1bc625-a965-412c-a913-4189db0dff48)

In my case I did not do what is in the image, I just installed the package and imported it into App.tsx.

my steps were:
1. Install the package
npm i react-native-haptic-feedback
2. Import into App.tsx file
import ReactNativeHapticFeedback from "react-native-haptic-feedback";
3. Use it inside the App.tsx file
// Optional configuration
const options = {
   enableVibrateFallback: true,
   ignoreAndroidSystemSettings: false,
};

// Trigger haptic feedback
ReactNativeHapticFeedback.trigger("impactLight", options);

Configurations in Smartphone Android:

1. Enable vibration

![image](https://github.com/jotalexvalencia/RollTheDice5/assets/10563766/62a51811-8c8b-4ef7-b4bb-44b624a7abc4)

2. Enable haptic feedback

![image](https://github.com/jotalexvalencia/RollTheDice5/assets/10563766/f929fb84-f930-4978-8058-442a015c3806)

3. Disable battery saver

![image](https://github.com/jotalexvalencia/RollTheDice5/assets/10563766/8a1763ce-d39e-41d3-8c5a-0a7a4b43f6dc)




