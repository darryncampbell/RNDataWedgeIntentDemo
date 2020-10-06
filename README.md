*Please be aware that this application / sample is provided as-is for demonstration purposes without any guarantee of support*
=========================================================

# RNDataWedgeIntentDemo
React Native example application demonstrating react-native-datawedge-intents module

This application demonstrates how to make use of the react-native-datawedge-intents module in your ReactNative Android application running on Zebra mobile computers.
The react-native-datawedge-intents modules can be found on
* [NPM](https://www.npmjs.com/package/react-native-datawedge-intents)
* [GitHub](https://github.com/darryncampbell/react-native-datawedge-intents)

### Installation

```bash
git clone https://github.com/darryncampbell/RNDataWedgeIntentDemo.git
cd RNDataWedgeIntentDemo
npm install
react-native run-android
```

### Usage
**Make sure you have DataWedge running on your device and configured with the Barcode input plugin enabled and the Intent output plugin as follows:**

![DataWedge](https://raw.githubusercontent.com/darryncampbell/react-native-datawedge-intents/master/screens/datawedge.png)

The UI is self-explanatory.  Buttons are provided for each action provided by the API.  The API maps to the [DataWedge API](http://techdocs.zebra.com/datawedge/5-0/guide/api/) 1:1.  Successful scans will be shown at the top of the app UI.  You can test everything is working by ensuring 'Enumerate' returns sensible value(s).

![Running Application](https://raw.githubusercontent.com/darryncampbell/RNDataWedgeIntentDemo/master/screens/running.png) 

