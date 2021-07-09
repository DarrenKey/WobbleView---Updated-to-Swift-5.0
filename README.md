# WobbleView---Updated-to-Swift-5.0

WobbleView from https://github.com/dotintent/WobbleView updated to Swift 5.0. 

## Installation

Just drag WobbleView.swift into your own project.

**Quoting from the original project:
**


## Usage

Just create a WobbleView and change its position.  

```swift
self.wobbleView.frame.origin = CGPoint(x: randomX, y: randomY)
```

or

```swift
self.wobbleView.center = CGPoint(x: randomX, y: randomY)
```

or animate the view's constraints.

## Properties

```swift
internal var frequency: CGFloat = 3
```

The frequency of oscillation for the wobble behavior.

```swift
internal var damping: CGFloat = 0.3
```

The amount of damping to apply to the wobble behavior.

```swift
var edges: ViewEdge = ViewEdge.Right
```

A bitmask value that identifies the edges that you want to wobble. You can use this parameter to wobble only a subset of the sides of the rectangle.
