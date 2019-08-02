# HYFullScreenImageViewer
Clicking on profile images, image in carousel, banner, cover photo etc.. You want this image to open in a full screen mode with ability to zoom by double tapping or using two fingers :D close by clicking a close button or just by dragging the image to get back to its original place with some cool animation

# TO-DO
1. Refactoring
2. Find better name for this repository
3. Fix animation
4. Force touch to load web page if image has link
5. Add documentation

# Usage
On your desired action, just create an instance from HYFullScreenImage passing it your image view. Example:

`let viewController = HYFullScreenImage(imageView: self.driverProfileImage);
viewController.presentInCurrentKeyWindow()`
