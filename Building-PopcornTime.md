### Requirements

* A Mac, preferably running the latest version of OS X (currently 10.11.x El Capitan)
* [Xcode 8.0+](https://itunes.apple.com/app/xcode/id497799835)
* tvOS/iOS 9.0+
* [Free Apple Developer Account](https://developer.apple.com/enroll/)
* USB-C cable if building for Apple TV

## Downloading the project

Clone the latest version of the repo using Terminal. You can expect bugs this way as the latest version of the repo is always seen as a work in progress.

```
cd ~/Desktop
git clone https://github.com/PopcornTimeTV/PopcornTimeTV.git
```

## Installing Dependencies

Run the Swift Install script with the following commands
```
cd ~/Desktop/PopcornTimeTV
swift install.swift
```
Follow the instructions to get setup and running.

Note: You can always re-run the install script to update to the latest available version as well.

## Opening the project

![Opening Project](https://camo.githubusercontent.com/96d202cca8e912d77333b1fd2c21fbb440fd49e6/687474703a2f2f692e6375626575706c6f61642e636f6d2f384b6a5734672e706e67)

Open the project using **PopcornTime.xcworkspace**


## Changing the Bundle Identifier

Click on the Project icon and select a target. If you want to install the iOS version select `PopcornTimeiOS`, if you want to install tvOS version, select `PopcornTimetvOS`.

![Target](https://i.imgur.com/9DX63O0.png)

Change the default bundle identifier to **com.NAMEHERE.popcorntime.PLATFORMHERE**

Change NAMEHERE to your name and PLATFORMHERE to the platform you are buidling for (iOS/tvOS)

## iOS:

Select the iOS scheme in the dropdown menu in Xcode. 

![Select Scheme](https://i.imgur.com/108RPdu.png)

Clicking the **Play** button or by pressing **CMD + R** will compile the project.

If you have any issues with the installation process, do not hesitate to [create an issue](https://github.com/PopcornTimeTV/PopcornTimeTV/issues/new)

## tvOS:

To compile for tvOS, you will need to change the `TopShelf` target's Bundle Identifier also.

Change the default bundle identifier to **com.NAMEHERE.popcorntime.PLATFORMHERE.TopShelf**

It is **imperitive** that you do not deviate from the bundle identifier examples. If the `PopcornTimetvOS` Bundle Identifier does not match up with the `TopShelf` Bundle Identifier, the project will not compile.



Select the tvOS scheme in the dropdown menu in Xcode. 

![Select Scheme](https://i.imgur.com/2xBDM2T.png)

Clicking the **Play** button or by pressing **CMD + R** will compile the project.

If you have any issues with the installation process, do not hesitate to [create an issue](https://github.com/PopcornTimeTV/PopcornTimeTV/issues/new)