# Hello World — Android (JavaScript / Expo)

A minimal "Hello, World!" Android app built with [Expo](https://expo.dev) and React Native (JavaScript).

## Prerequisites

- [Node.js](https://nodejs.org/) 18+
- The [Expo Go](https://expo.dev/client) app on your Android phone, **or** an Android emulator via Android Studio

## Run it

```bash
npm install
npm run android
```

- If you have Expo Go installed on a physical Android device, scan the QR code printed in the terminal.
- If you have an Android emulator set up, `npm run android` will launch it automatically.

## Project structure

- `App.js` — the app's single screen, rendering "Hello, World!"
- `app.json` — Expo app configuration (name, icon, Android settings)
- `index.js` — Expo entry point that registers the root component
