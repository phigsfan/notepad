# Tools:
- npx (with "react-native" prefix for sub commands)
- npm (succint version)

The code generating process is mostly command line driven, a few tools are necessary (They tend to be half baked), such as 'metro', 'npx' (Node Package eXecute), etc.

## Android
- npx react-native run-android  (npm run android)

## IOS
- 'sudo xcode-select -s /Applications/Xcode.app/Contents/Developer' (switch to the command line tool to my installation dir)
- change the bundle name to an unique one for signing (default will not work).
  ('npx react-native-rename "FirstProj" -b "com.$myname.react.$my-second")
- (not totally sure this is necessary) open xcode proj and register the bundle id (for the proj and its companion test proj: 2 projects).
- npx react-native run-ios (npm run ios)
- verify the app (newly installed) on iPhone device (Setting -> General -> VPN & Device Management)

# References
# Metro
- From [Medium][metro-medium-link]
## Android
- https://reactnative.dev/docs/environment-setup?guide=native&platform=android


## IOS
- https://aka.ms/ReactNativeGuideMacOS


[metro-medium-link]: https://omurbilgili.medium.com/unveiling-the-power-of-metro-bundler-in-react-native-bf68d151f063#:~:text=The%20Metro%20Bundler%20is%20the,or%20packaging%20it%20for%20production
