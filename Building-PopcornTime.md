### Requirements

* A Mac, preferably running the latest version of OS X (currently 10.11.x El Capitan)
* Xcode 7.3+
* tvOS 9.2+
* Free Apple Developer Account
* USB-C cable if building for Apple TV

### Downloading the project

Clone the latest version of the repo using Terminal. You can expect bugs this way as the latest version of the repo is always seen as a work in progress.

```
cd ~/Desktop
git clone https://github.com/PopcornTimeTV/PopcornTimeTV.git
```

### Installing Dependencies


You're going to need to install Cocapods, run the following command in Terminal.
```
gem install cocoapods
```
After Cocoapods successfully installs continue to run the following commands
```
cd ~/Desktop/PopcornTimeTV
pod install
```
Alternatively, you can use the Swift Install script with the following commands
```
cd ~/Desktop/PopcornTimeTV
swift install.swift
```
Follow the instructions to get setup and running.

Note: You can always run this script to also update your current copy.

### Opening the project

![Opening Project](https://camo.githubusercontent.com/96d202cca8e912d77333b1fd2c21fbb440fd49e6/687474703a2f2f692e6375626575706c6f61642e636f6d2f384b6a5734672e706e67)

Open the project using **PopcornTime.xcworkspace**

### Changing the Bundle Identifier

![Bundle ID](https://camo.githubusercontent.com/92a24ac63146294e5c1e554022baee099f6fb6c6/687474703a2f2f692e6375626575706c6f61642e636f6d2f7247374830452e706e67)

Change the default bundle identifier to **com.NAMEHERE.popcorntime**

You will need to use the same Bundle Identifier for the TopShelf extension below

![Select](https://camo.githubusercontent.com/f7a772b73993aad4ee9c4fce3da0e20b73c269d4/687474703a2f2f692e6375626575706c6f61642e636f6d2f65505434796f2e706e67)

![ID](https://camo.githubusercontent.com/9752b4ab89d2de329c8fabea26d41165c5855f9e/687474703a2f2f692e6375626575706c6f61642e636f6d2f4676565574572e706e67)

Change the default bundle identifier to **com.NAMEHERE.popcorntime.TopShelf**
![Top shelf](https://camo.githubusercontent.com/ab25ea25bd5810ae498f99816f4ed9490065d577/687474703a2f2f692e6375626575706c6f61642e636f6d2f417a433354322e706e67)
Clicking the **Play** button or by pressing **CMD + R** will compile the project