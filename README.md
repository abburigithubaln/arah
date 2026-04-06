# React Native Responsive Login Page

This project uses **React Native with Expo** and includes a responsive login screen built to adapt across phones, tablets, and web.

## Run

```bash
npm install
npm run start
```

Then open on:
- Android emulator/device
- iOS simulator/device
- Web browser (`npm run web`)

## Responsiveness approach

- `SafeAreaView` to handle notches and system UI areas.
- `KeyboardAvoidingView` so fields remain usable while typing.
- `useWindowDimensions()` to adapt card width by device size.
- `ScrollView` to prevent clipping on small screens.
