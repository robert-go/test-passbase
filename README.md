# test_passbase

## Xcode 12.5.1

## Simulator iPhone 12 Pro Max 14.5

## Flutter SDK: 2.7.4-nullsafety.0

## Error
```
Launching lib/main.dart on iPhone 12 Pro Max in debug mode...
Running pod install...                                           1,228ms
Running Xcode build...                                                  
Xcode build done.                                            6.0s
Failed to build iOS app
Error output from Xcode build:
↳
    ** BUILD FAILED **


Xcode's output:
↳
    warning: [CP] Unable to find matching .xcframework slice in '/Users/minhdrminh/Projects/test-passbase/ios/Pods/Passbase/Passbase.xcframework Passbase framework ios-arm64 ios-x86_64-simulator' for the
    current build architectures (arm64 x86_64).
    /Users/minhdrminh/flutter/.pub-cache/hosted/pub.dartlang.org/passbase_flutter-2.7.4/ios/Classes/SwiftPassbaseFlutterPlugin.swift:3:8: error: no such module 'Passbase'
    import Passbase
           ^
    note: Using new build system
    note: Building targets in parallel
    note: Planning build
    note: Analyzing workspace
    note: Constructing build description
    note: Build preparation complete
    /Users/minhdrminh/Projects/test-passbase/ios/Pods/Pods.xcodeproj: warning: The iOS Simulator deployment target 'IPHONEOS_DEPLOYMENT_TARGET' is set to 8.0, but the range of supported deployment target
    versions is 9.0 to 14.5.99. (in target 'Flutter' from project 'Pods')

Could not build the application for the simulator.
Error launching application on iPhone 12 Pro Max.
```