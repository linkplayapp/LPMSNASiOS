# LPMSNASiOS

[English](README.md) | [中文](README_zh.md)

LPMSNAS是Linkplay NAS接入方案的app端SDK；通过它，您可以快速的将NAS设备的音乐播放到您的产品里。

LPMSNAS主要提供了两个功能：

- 展示NAS设备中的音乐

- 播放NAS设备中的音乐到您的产品里

## 文档

你可以在这里找到更多[文档](https://linkplayapp.github.io/linkplay_sdk_doc/zh-hans/introduction.html) 。

## 示例

如果您要执行示例工程，请clone工程并使用`pod install`安装必要库。

## 需求

- iOS >= 10.0

## 安装

LPMSNASiOS 可以通过 [CocoaPods](https://cocoapods.org) 安装. 将下面的代码添加到您的pod文件里即可：

```ruby
platform :ios, '10.0'

target 'your_target_name' do

   pod "LPMSNASiOS", :git => "https://github.com/linkplayapp/LPMSNASiOS.git"

end
```

## 作者

LinkPlay, ios_team@linkplay.com
