
# What is enMoLog?

Are you facing lot of UAT/production issues in your mobile application which are not reproducible at developer side? Would you like to get instant logs from your user regarding the actions, variable values which are resulting in the bug? enMoLoger is the answer for you. It can even aggrigate the logs which when network is not availble, it can capture all the user activities before a crash happens.

# How to use enMoLog?
Create an account and generate an API key at <https://enmolgger.enwidth.com>
Use enMoLog SDK for iOS and Android.

# enMoLog SDK for iOS
You can use enMoLog SDK for iOS 9.0 and later.

# Integrating SDK with iOS
##### Using CocoaPods
- Setup CocoaPod for your project following the insructions from <https://guides.cocoapods.org/using/using-cocoapods>
- Add line in your Podfile pod 'RLLogger', :git => 'https://github.com/enwidth/enMoLog-ios-sdk.git'
- execute pod install command.

# Using in Swift Project

Import enMogLog in your AppDelegate 
```Swift
import RLLogger
```
Initialize the logger with API key
```Swift
RLLogManager.initialize(apiKey: "API_KEY")
```
You can log using below syntax. Other log levels are info, warn, error and fatal.
```Swift
RLog.debug("Log text")
```

You can chanege the log ever from https://enmolgger.enwidth.com

For any queries contact me at contact@enwidth.com

