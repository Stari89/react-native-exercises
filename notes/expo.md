# Expo

## Intro
It's a React native framework.

* Expo Go for development on machines

Supported platforms:
* Android
* iOS
* Web

## Creating New Project

```
npx create-expo-app@latest
```

You have many different templates, bu

## Debugging
```
npm run start
```

* Generates a QR code.
* Starts an HTTP server that serves your JavaScript bundle.
* Starts a WebSocket server for live reload, hot reload, logs, and debugging features.

### Android
* Install Expo Go from Google Play store.
* Open the Expo Go and scan the QR code.
* Enjoy!

### iOS
* Install Expo Go from App Store
* Scan the QR code with the Camera app.
* Enjoy!

### Web
* Just copy-paste the development server's IP to your browser.
* Enjoy!

Now that Expo Go has loaded your JS, it's in constant communication with your machine.

* Logs from the app show up in your terminal or browser.
* Code changes trigger live reload or hot reload via WebSocket.
* You can enable Remote Debugging — this runs your JS code inside Chrome DevTools instead of on the device, letting you inspect variables, use breakpoints, etc.
* You can enable React DevTools and the new Expo debugger (expo-dev-client or Flipper for more advanced setups).

Why is this powerful?
* No native build step needed.
* You can test on a physical device in seconds.
* Debugging feels like web development.
* You can work without a USB cable, just over WiFi.

Downsides of Expo Go Debugging
* It's a sandboxed environment → You can't use custom native code (native modules not included in Expo Go).
* Performance in debug mode is not identical to production.
* If you need native code, you need to eject to Expo Bare Workflow.

## Building artifacts

* EAS build
* without EAS https://docs.expo.dev/build-reference/local-builds/
    * sadf

## Distribution (QA testing)