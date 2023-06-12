# Steps To Reproduce

1. Follow the instructions here to create a new react native v0.71 macOS app: https://microsoft.github.io/react-native-windows/docs/rnm-getting-started
   1. `npx react-native init webViewTest --template react-native@^0.71.0`
   2. `cd webViewTest`
   3. `npx react-native-macos-init`
2. Follow the instructions here to add react-native-webview to the app: https://github.com/react-native-webview/react-native-webview/blob/master/docs/Getting-Started.md
   1. `$ yarn add react-native-webview`
   2. `$ cd ios && pod install && cd ..`
   3. Copy the the "Import the webview into your component" code into `MyWeb.js` and import it into `App.tsx`
3. Run the app with `npx react-native run-macos` and see that the web view is not displayed but there are no visible errors
