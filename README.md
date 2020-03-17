## Getting started

`$ npm install react-native-doc-viewer --save`

### Automatic installation

`$ react-native link react-native-doc-viewer`

### CocoaPods installation

If your project uses CocoaPods to manage React installation (especially with Expo-detached project), most likely you will run into issue with header files not found as described here (https://docs.expo.io/versions/latest/guides/expokit.html#changing-native-dependencies "Changing Native Dependencies"). It will be helpful to follow these steps to have it compiled successfully:

1. `npm install react-native-doc-viewer --save`

2. Add the plugin dependency to your Podfile, pointing at the path where NPM installed it:

`pod 'RNReactNativeDocViewer', path: '../node_modules/react-native-doc-viewer'`

3. Run `pod install`