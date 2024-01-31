# Set up the Repro

1. Clone this repository, then run the following commands:
```sh
yarn install
cd ios
bundle install
RCT_NEW_ARCH_ENABLED=1 bundle exec pod install
cd ..
git apply patches/react-native-safe-area-context.patch
open ios/TestLibs.xcworkspace
yarn start
```
In Xcode, open the AppDelegate and enable BridgelessMode.

Run from Xcode
