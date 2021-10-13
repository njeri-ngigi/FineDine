# FineDine

## Running the app

### Step 1: Start Metro

First, you will need to start Metro, the JavaScript bundler that ships with React Native. Metro "takes in an entry file and various options, and returns a single JavaScript file that includes all your code and its dependencies." — [Metro Docs](https://facebook.github.io/metro/docs/concepts)

- run `yarn start`

### Step 2: Start Application in Android

To run the app on an **android simulator**:

- run `yarn android`

To run the app on an **android device**:

- Enable debugging via usb on your android device
- Connect device via usb cable
- run `adb devices` to check if device is available
- run `yarn android`

To connect via WiFi follow [this doc](https://reactnative.dev/docs/running-on-device)

### Step 3: Start Application in IOS

To run the app on an **xcode simulator**:

- cd into the ios folder
- run `open FineDine.xcworkspace`
- pick a device and click on the play button

To run the app on an **ios device**:

- Follow in instructions on [this doc](https://reactnative.dev/docs/running-on-device)
