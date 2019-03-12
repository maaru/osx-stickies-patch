**[OBSOLETE] _OS X Yosemite fixed this issue! This path is no longer needed._**

osx-stickies-patch
=====
* Stickies.patch
    * Fix issue that background color is reverted to default yellow at restart. This problem occurs only in the retina display.
    * 1. Copy Stickies.patch to local. (example, ~/Downloads/Stickies.patch)
    * 2. Run patch command. (sudo patch /Library/Widgets/Stickies.wdgt/Stickies.js < ~/Downloads/Stickies.patch)
