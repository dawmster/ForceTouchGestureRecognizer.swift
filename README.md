# ForceTouchGestureRecognizer
UIGestureRecognizer subclass enabling 3D Touch
## Installation
### CocoaPods
[CocoaPods][] is a dependency manager for Cocoa projects. To install Reachability.swift with CocoaPods:

 1. Make sure CocoaPods is [installed][CocoaPods Installation].

 2. Update your Podfile to include the following:

    ``` ruby
    pod 'ForceTouchGestureRecognizer', git: 'https://github.com/ashleymills/ForceTouchGestureRecognizer'
    ```

 3. Run `pod install`.

[CocoaPods]: https://cocoapods.org
[CocoaPods Installation]: https://guides.cocoapods.org/using/getting-started.html#getting-started

### Manual
Just drop the **ForceTouchGestureRecognizer.swift** file into your project. That's it!

## Example

````
        let forceTouchGesture = ForceTouchGestureRecognizer()
        forceTouchGesture.addTarget(self, action: "pressView:")
        forceTouchGesture.minimumValue = 0.1
        view.addGestureRecognizer(forceTouchGesture)

````

## Want to help?

Got a bug fix, or a new feature? Create a pull request and go for it!

Cheers,
Ash

