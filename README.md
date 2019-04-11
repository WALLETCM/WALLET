# Wallet.cm Mobile 

This is the main mobile application for Wallet.cm. This is a React Native application that will be able to be deployed on both iOS and Android.

### Running application for local development
- Ensure [yarn](https://yarnpkg.com) is installed in your development environment
- `yarn` to install dependencies
- `yarn start` to start packaging server
- `yarn ios` or `yarn android` to install and the application on a simulator, for iOS and Android respectively
  - ***Note**: The process for running the android simulator is a bit more complicated than the ios side. Please see the "Building Project with Native Code" tab of the [getting started React Native documentation](https://facebook.github.io/react-native/docs/getting-started.html)*


### Installing on a device
See the following guides for generating a package for deployment

- [Android](https://facebook.github.io/react-native/docs/signed-apk-android.html)
- [iOS, read "Archiving Your App"](https://developer.apple.com/library/content/documentation/IDEs/Conceptual/AppDistributionGuide/TestingYouriOSApp/TestingYouriOSApp.html)

The generated .apk or .ipa can then be uploaded to Wallet.cm App account for testing.


### Running tests
`yarn test`
