##AutoScrollLabel

Provides auto scrolling for text that may be clipped by the view. iOS 4.0 and greater, it can be easily migrated to ARC.

[http://blog.stormyprods.com/2009/10/more-details-on-autoscrolllabel-usage.html](http://blog.stormyprods.com/2009/10/more-details-on-autoscrolllabel-usage.html) - Old, but still relevant example usage.

Usage:
    
    autoScrollLabel.text = @"This text may be clipped, but now it will be scrolled.";
    autoScrollLabel.textColor = [UIColor blueColor];
    autoScrollLabel.labelSpacing = 35; // distance between start and end labels
    autoScrollLabel.pauseInterval = 3.7; // seconds of pause before scrolling starts again
    autoScrollLabel.scrollSpeed = 30; // pixels per second
