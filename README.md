# iOS Demo App

## Introduction 

The Demo App is reference implementation of the [OstWalletSdk](https://github.com/ostdotcom/ost-wallet-sdk-ios). This App is meant to be a technical reference- please refer to [dev.ost.com](dev.ost.com) for full SDK references and workflows. 

## Dependencies

### Cocoapod 
Run below command to pull all dependencies in `Podfile`:

```
pod install
```

### Carthage
[OstWalletSdk](https://github.com/ostdotcom/ost-wallet-sdk-ios) is released under [Carthage](https://github.com/Carthage/Carthage). So, OstWalletSdk and dependencies may be pulled by:
```
carthage update --platform ios
```

## Application Setup

- Assign appropriate value for `OST_PLATFORM_API_ENDPOINT` present in [info.plist](TestDemoApp/Info.plist). 
- Assign appropriate value for `MAPPY_APP_SERVER_URL` present in [info.plist](TestDemoApp/Info.plist). 
- Please refer to [Application Server API specifications](MappyServerSpecification.md) and set up a server to serve responses in the specified format to run the application.
