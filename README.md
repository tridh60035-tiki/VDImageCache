# VDImageCache

[![CI Status](http://img.shields.io/travis/dvvu/VDImageCache.svg?style=flat)](https://travis-ci.org/dvvu/VDImageCache)
[![Version](https://img.shields.io/cocoapods/v/VDImageCache.svg?style=flat)](http://cocoapods.org/pods/VDImageCache)
[![License](https://img.shields.io/cocoapods/l/VDImageCache.svg?style=flat)](http://cocoapods.org/pods/VDImageCache)
[![Platform](https://img.shields.io/cocoapods/p/VDImageCache.svg?style=flat)](http://cocoapods.org/pods/VDImageCache)

![](https://www.unh.edu/dining/sites/www.unh.edu.dining/files/media/images/Pay-Cats-Cache/cats-cache.png)
## Description

VDImageCache can help you cache image, We can config save on disk or mem.

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.
Read example

## How to use

To store image

    [[VDImageCache sharedInstance] storeImage:[UIImage imageNamed:@"test.png"] withKey:@"identifier"];
To get image

    [[VDImageCache sharedInstance] imageFromKey:_identifier storeToMem:BOOL]
To getImage with size

    [[VDImageCache sharedInstance] imageFromKey:_identifier withSize:CGSizeMake(a, b)]
## Requirements

IOS 8 or later.
## Installation

VDImageCache is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'VDImageCache','https://github.com/dvvu/VDImageCache.git'
```

## Author

dvvu, doanvanvu9992@gmail.com

## License

VDImageCache is available under the MIT license. See the LICENSE file for more info.
