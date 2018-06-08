# MagnifyView
[![Version](https://img.shields.io/cocoapods/v/NotificationBannerSwift.svg?style=flat)](http://cocoapods.org/pods/NotificationBannerSwift)
![](https://img.shields.io/badge/language-swift-blue.svg)
![](https://img.shields.io/badge/version-4.0-red.svg)

## About:
| MagnifyView | 
| ------------- | 
| ![MagnifyView](ezgif.com-resize.gif) | 

## Installation:
### • CocoaPods
LoginHelper is available through CocoaPods. To install it, simply add the following line to your Podfile:
```
pod "MagnifyView"
```
## Getting Started:
Select the view you want to magnify, and embed it in another view. Set the views class to YPMagnifyingGlass, and connect it to an IBOutlet property in your UIViewController (or whatever else). In this example you call the connected view magnifyingView.

Then in your code, add
```
var magnifyingGlass = MagnifyingGlass(frame:CGRectMake(magnifyingView.frame.origin.x, magnifyingView.frame.origin.y,100,100))
mag.scale = 2
self.magnifyingView.magnifyingGlass = mag
 addMagnifyingGlassAtPoint(point: #point)
 magnifyingGlass.touchPoint = #point
 magnifyingGlass.setNeedsDisplay()
```
