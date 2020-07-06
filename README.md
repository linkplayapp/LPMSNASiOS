# LPMSNASiOS

[English](README.md) | [中文](README_zh.md)

LPMSNAS is the app side SDK for Linkplay NAS access solution；you can use it to quickly play music from NAS devices to your products.

LPMSNAS mainly provides two functions：

- Show music from NAS devices.

- Play music from NAS device to your product.

## Documentation

You can find documentation [on the website](https://linkplayapp.github.io/linkplay_sdk_doc/en/).

## How To Get Started

- [Download LPMSNASiOS](https://github.com/linkplayapp/LPMSNASiOS/archive/master.zip) and import SDK to your project

## SDK Demo
###  1. SDK demo with CocoaPods
- [LPMusicKitPodsDemo](https://github.com/linkplayapp/LPMusicKitPodsDemo)

###  2. SDK demo
- [LPMusicKitDemo](https://github.com/linkplayapp/LPMusicKitDemo)

## Requirements

- iOS >= 10.0

## Installation

###  1. Installationwith CocoaPods

LPMSNASiOS is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
platform :ios, '10.0'

target 'your_target_name' do

   pod "LPMSNASiOS", :git => "https://github.com/linkplayapp/LPMSNASiOS.git"

end
```
Then run the `pod update` command in the root directory of project.
For use of CocoaPods, please refer to the [CocoaPods Guides](https://guides.cocoapods.org/). It is recommended to update the CocoaPods to the latest version.

### 2. Manually configure your project

#### Step 1: Download LPMSNASiOS

- [Download LPMSNASiOS](https://github.com/linkplayapp/LPMSNASiOS/archive/master.zip)

#### Step 2: Import Framework

- Import LPMSNAS.framework, and its dependent SDK: [LPMusicKitiOS](https://github.com/linkplayapp/LPMusicKitiOS)、[LPMDPKitiOS](https://github.com/linkplayapp/LPMDPKitiOS)

## Author

LinkPlay, ios_team@linkplay.com
