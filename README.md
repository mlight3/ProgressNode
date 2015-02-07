# ProgressNode
A circular progress timer for SpriteKit games written in swift.

## How shoud you use
Just add the file to your project, and customize as you want.

```swift
let example             = ProgressNode()
example.radius          = 20.0
example.width           = 5.0
example.color           = SKColor(hex: 0x4183D7)
example.backgroundColor = SKColor(hex: 0x6BB9F0)
example.position        = CGPoint(x: CGRectGetMidX(self.frame), y: CGRectGetMidY(self.frame))

example.countdown(time: 10.0) { () -> Void in
    NSLog("Completed.")
}

self.addChild(example)
```

## How it looks like
![alt tag](https://pbs.twimg.com/media/B9MxNVHIMAA1JCY.jpg)

## License
WTFPL
