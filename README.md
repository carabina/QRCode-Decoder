# QRCode-Decoder

[![CocoaPods Compatible](https://img.shields.io/cocoapods/v/DYQRCodeDecoder.svg)](https://img.shields.io/cocoapods/v/DYQRCodeDecoder.svg)
[![Platform](https://img.shields.io/cocoapods/p/DYQRCodeDecoder.svg)](http://cocoadocs.org/docsets/DYQRCodeDecoder)
[![Twitter](https://img.shields.io/badge/twitter-@DwarvenYang-blue.svg)](http://twitter.com/DwarvenYang)
[![License](https://img.shields.io/github/license/Dwarven/QRCode-Encoder.svg)](https://img.shields.io/github/license/Dwarven/QRCode-Encoder)

An iOS QRCode Scanner and Decoder

 - Looking for an iOS QRCode Image Encoder? Check this! [https://github.com/Dwarven/QRCode-Encoder]

# Preview
<img src="https://raw.githubusercontent.com/Dwarven/QRCode-Decoder/master/FromCamera.gif" width="230" align="center" style="margin:10px">
<img src="https://raw.githubusercontent.com/Dwarven/QRCode-Decoder/master/FromImage.gif" width="230" align="center" style="margin:10px">

# Podfile
To integrate QRCode-Decoder into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
pod 'DYQRCodeDecoder'
```


# How to use

```obj-c
#import "DYQRCodeDecoderViewController.h"

DYQRCodeDecoderViewController *vc = [[DYQRCodeDecoderViewController alloc] init];
[vc setCompletion:^(NSString *result) {
   NSLog(@"%@", result);
}];
UINavigationController *navVC = [[UINavigationController alloc] initWithRootViewController:vc];
[self presentViewController:navVC animated:YES completion:NULL];

```
**Enjoy**

