# cordova-plugin-barcode-qrscanner

> A fast, energy efficient, highly-configurable QR code + barcode scanner for Cordova / Ionic apps – available for the iOS, Android, Windows, and browser platforms.

> Support also CODE_39, CODE_93, CODE_128 standards

> Supports Android API level 32
---

Works as of **January 2023**.

Original project & documentation: https://www.npmjs.com/package/cordova-plugin-qrscanner

```
ionic@6
cordova@11
cordova-ios@6
cordova-android@11
angular@14
```

Original plugin/repo is `https://github.com/bitpay/cordova-plugin-qrscanner`. It was not working with the latest Android/iOS version. _It failed during XCode build._

Other packages on npm with apparent solutions kept installing the original plugin. _So they fail during XCode build, too._

---

**This is a fork of https://github.com/gianluigitrontini/cordova-plugin-qrscanner-nbs. That fork was forked from https://github.com/v1934/cordova-plugin-qrscanner-11, with a commit taken from https://github.com/NoahSun/cordova-plugin-qrscanner.**

**This plugin is working with the latest android and ios platform and contains fixes for compilation errors due to incompatibilities with Swift 5 and Android API level 32**

---

If you're using Ionic, switch to Capacitor.
