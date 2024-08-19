# ExpoSplashScreenNotShowing

This is a minimal reproducible example of the issue I'm facing with Expo SDK 51

## Steps to reproduce

1. Clone this repo
```bash
git clone https://github.com/gabriel-logan/ExpoSplashScreenNotShowing.git
```

2. Install dependencies
```bash
cd ExpoSplashScreenNotShowing

npm install
```

3. Bundle the app
```bash
eas build --platform android --profile preview
```

4. Install the apk on a device

5. Open the app

## Expected behavior

The splash screen should be shown

## Actual behavior

The splash screen is not shown

## Additional information

Using this reproducible exemple - [Manual Setup Branch](https://github.com/gabriel-logan/ExpoSplashScreenNotShowing/tree/manualset)

The splash screen is shown, but I have to manually set the splash screen in the app.tsx file
