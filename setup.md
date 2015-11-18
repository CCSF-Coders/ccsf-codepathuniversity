# Setting up your Mac for iOS app development
Students will need:

1. **Mac computer** running OS X 10.10.5 or later (required to download Xcode 7). 

  > **_If you are upgrading your operating system, remember to backup existing iOS projects, software keys, etc -- ideally on an external hard drive_**.  
  > _If you have specialty software (video editing software, etc), please check with the user and support communities to verify the compatible versions of OS X *before* upgrading._

1. **Xcode** -- the integrated development environment (IDE) from Apple for making software for iOS and OS X
  - First check to see if you already have Xcode installed on your Mac (look in your Applications folder):
    - if you already have Xcode, open the software to see which version number you have
    - if you don't, follow this link: https://developer.apple.com/xcode/download/
      - Here you will be asked to [create an Apple Developer account](https://developer.apple.com/register/index.action).
        + If you already have an Apple ID, you can sign in with this.
        + You only need the free version. 
        + However, if you want to release your app in the app store, you will have to enroll in the [iOS Developer Program](https://developer.apple.com/programs/start/standard/).  This costs $99 a year.
      - If you have slow internet downloading Xcode could take 10 hours; however, if not, it should take 10 minutes. If you find yourself with a 10hr download time go to your local Apple store (free wifi and no password required).

1. **git** -- a [version control system](https://en.wikipedia.org/wiki/Version_control) for software development
  - First check to see if you already have git installed on your Mac:
    - open the Terminal program (look in Applications > Utilities)
    - type:
    
      > git --version
    
    - if you have git already installed on your Mac, then you will see a result like this:
    
      > git version 2.6.2
    
    - for any other result, Ctrl + C to escape back to "the command line" ([more about the command line](./command-line.md))
  - if you need to install git on your Mac, follow this link: http://git-scm.com/downloads
    - the *easiest* way to check if the installation worked:
      - open a \*new* Terminal window, and
      - again type:
      
        > git --version

#### Optional (more detail coming later)
1. [Homebrew](http://brew.sh/)
1. [CocoaPods](http://cocoapods.org)

---
### Now make your [first iOS app](first.md) or return to the [main page](README.md).
