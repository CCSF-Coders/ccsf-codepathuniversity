# Using images in your iOS apps
- png images are the preferred format
- all the image assets should go into the Assets.xcassets folder
 - check out these guides:  
    - https://github.com/codepath/ios_guides/wiki/Adding-Image-Assets
    - https://github.com/codepath/ios_guides/wiki/Using-UIImageView
 - the best and easiest way is just to drag the assets from the finder into the Assets.xcassets folder

- There is a naming convention that tells Xcode the resolution a particular image was intended for. you will often see things like, my_pic<i></i>@1x.png or my_pic<i></i>@2x.png. Xcode will automatically put those in the correct “slot” and manage them appropriately. 1x is for the iphone 3, 2x for retina 4-6 and 3x for 6plus
  - if you are really curious:
https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/IconMatrix.html

- if you are importing your own pics, you can name them pretty much whatever you want, just make sure they are .png

- you actually want as few actual image files in your app as possible because image assets take a ton of memory relative to pulling them down from a network. icons and stuff that will stay static and you need to appear instantly are good assets to have locally. Dynamic content is best to get from a network call.

- 

### Return to the [resources](resources.md) page or to the [main page](README.md).
