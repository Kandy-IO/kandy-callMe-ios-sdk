# Kandy Link Anonymous iOS SDK

<p>
    <img alt="Cocoapods platforms" src="https://img.shields.io/cocoapods/p/KandyLinkMobileSDKAnonymous">
    <img alt="GitHub release (latest SemVer)" src="https://img.shields.io/github/v/release/kandy-io/kandy-anonymous-ios-sdk">
    <img alt="Cocoapods" src="https://img.shields.io/cocoapods/v/KandyLinkMobileSDKAnonymous">
</p>

## Install

### CocoaPods

[CocoaPods](https://cocoapods.org/pods/KandyLinkMobileSDKAnonymous) is a dependency manager for Cocoa projects. For usage and installation instructions, visit their website. To integrate *Kandy Link Anonymous iOS SDK* into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
...
use_frameworks!

target 'YOUR_TARGET_NAME' do
    pod 'KandyLinkMobileSDKAnonymous', '~> 5.20.0'
end

post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['ENABLE_BITCODE'] = 'NO'
    end
  end
end

...
```

### Manual

Alternatively *Kandy Link Anonymous iOS SDK* can be manually integrated to your project with the [followed steps](https://kandy-io.github.io/kandy-link-ios-sdk/tutorials/#/?id=manual-installation-after-v5170). 

## Documentation

The information about tutorials and documents can be found in the links below

* Documents: [API Docs](https://kandy-io.github.io/kandy-anonymous-ios-sdk/docs)

* Tutorials: Choose your configuration ( [Kandy-US](https://kandy-io.github.io/kandy-anonymous-ios-sdk/tutorials/?SUBSCRIPTIONFQDN=webrtc-na.kandy.io&WEBSOCKETFQDN=webrtc-na.kandy.io&ICESERVER1=turn-na-1.kandy.io&ICESERVER2=turn-na-2.kandy.io) | [Kandy-EMEA](https://kandy-io.github.io/kandy-anonymous-ios-sdk/tutorials/?SUBSCRIPTIONFQDN=webrtc-em.kandy.io&WEBSOCKETFQDN=webrtc-em.kandy.io&ICESERVER1=turn-em-1.kandy.io&ICESERVER2=turn-em-2.kandy.io) | [Kandy-UAE](https://kandy-io.github.io/kandy-anonymous-ios-sdk/tutorials/?SUBSCRIPTIONFQDN=ct-webrtc.etisalat.ae&WEBSOCKETFQDN=ct-webrtc.etisalat.ae&ICESERVER1=ct-turn1.etisalat.ae&ICESERVER2=ct-turn2.etisalat.ae) )

## Compatibility

Compatible iOS versions :

* iOS 11.x+

Compatible XCode Versions :

* XCode 12.x+

Compatible KandyLink Server versions :

* Kandy Link 4.7.1 Patch 6

* Kandy Link 4.8 Patch 4

Tested on :

* iPhone 6S, 7, 7+, 8, X, iPad mini, and iPad Air
