Expo Router Web App With Camera Crashes
-

## Sample App
- using router starter template tabs@50
- add camera code from expo-camera
- npm run web
- See Error Below

## Error
```
Call Stack
createWorkerAsyncFunction
node_modules/expo-camera/build/useWebQRScanner.js:46:20
<global>
node_modules/expo-camera/build/useWebQRScanner.js:57:16
loadModuleImplementation
node_modules/metro-runtime/src/polyfills/require.js:273:5
guardedLoadModule
node_modules/metro-runtime/src/polyfills/require.js:180:12
metroRequire
node_modules/metro-runtime/src/polyfills/require.js:89:7
<global>
node_modules/expo-camera/build/ExpoCamera.web.js:10
loadModuleImplementation
node_modules/metro-runtime/src/polyfills/require.js:273:5
guardedLoadModule
node_modules/metro-runtime/src/polyfills/require.js:180:12
metroRequire
node_modules/metro-runtime/src/polyfills/require.js:89:7
<global>
node_modules/expo-camera/build/Camera.js:4
```