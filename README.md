# Set up the Repro

1. Clone this repository, then run the following commands
2. `yarn install`
3. `cd ios`
4. `bundle install`
5. `RCT_NEW_ARCH_ENABLED=1 bundle exec pod install`
6. `cd ..`
7. `git apply patches/react-native-safe-area-context.patch`
8. `open ios/TestLibs.xcworkspace`
9. `yarn start`

Run from Xcode
