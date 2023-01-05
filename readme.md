# cordova-plugin-qrscanner

> A fast, energy efficient, highly-configurable QR code + barcode scanner for Cordova / Ionic apps – available for the iOS, Android, Windows, and browser platforms.

> Support also CODE_39, CODE_93, CODE_128 standards

> Supports Android API level 32
---

Works as of **August 2022**.

```
ionic@6
cordova@11
cordova-ios@6
cordova-android@10
angular@14
```

Original plugin/repo is `https://github.com/bitpay/cordova-plugin-qrscanner`. Currently not working with the latest Android/iOS version. _It fails during XCode build._

Other packages on npm with apparent solutions keep installing the original plugin. _So they fail during XCode build, too._

---

**This is a fork of https://github.com/v1934/cordova-plugin-qrscanner-11, with a commit taken from https://github.com/NoahSun/cordova-plugin-qrscanner.**

**It's working with the latest android platform and contains fixes for compilation errors due to incompatibilities with Swift 5**

---

If you're using Ionic, switch to Capacitor.
