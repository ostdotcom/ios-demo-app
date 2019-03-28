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

- Assign appropriate value for `OST_PLATFORM_API_ENDPOINT` present in [info.plist](TestDemoApp/Info.plist). 
- Assign appropriate value for `MAPPY_APP_SERVER_URL` present in [info.plist](TestDemoApp/Info.plist). 
- Please refer [Mappy APP API](MappyServerSpecification.md) for setting up server to serve response in mentioned format to run the application.
