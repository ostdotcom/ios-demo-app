# iOS Demo App

## Introduction

Demo App is representation of how developer can use [OstWalletSdk](https://github.com/ostdotcom/ost-wallet-sdk-ios) in their application.
## Dependencies

### Cocoapod 
Run below command to pull all dependencies in `Podfile`:

```
pod install
```

### Carthage
[OstWalletSdk](https://github.com/ostdotcom/ost-wallet-sdk-ios) is released under [Carthage](https://github.com/Carthage/Carthage). So, OstWalletSdk and dependencies pulled by:
```
carthage update --platform ios
```

## Application Setup

- Assign appropriate value for `OST_Platform_API_ENDPOINT` present in [info.plist](https://github.com/ostdotcom/ios-demo-app/blob/develop/TestDemoApp/Info.plist). 
- Assign appropriate value for `MAPPY_APP_SERVER_URL` present in [info.plist](https://github.com/ostdotcom/ios-demo-app/blob/develop/TestDemoApp/Info.plist). 

