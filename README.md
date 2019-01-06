# Appium with Robot Framework

## Setup for appium
1.Install python 2.7.10 in your machine [Download Python](https://www.python.org/downloads/) 

2.set environment variable for python for directory C://python27 and C://python27/lib

3.Install wxpython for python(64bit) [Download WXPython](https://pypi.org/project/wxPython/)

4.[Install ride](https://pypi.org/project/robotframework-ride/) 
`pip install robotframework-ride`

5.Install selenium [Selenium Installtion Guide](https://selenium-python.readthedocs.io/installation.html)
`pip install selenium`

6.Install robot framework  [Robot Framework installation](https://pypi.org/project/robotframework/)

`pip install robotframework`

7.Install selenium 2 library [Selenium2 Library Guide](http://robotframework.org/Selenium2Library/Selenium2Library.html)

[Selenium2Library Installtion](https://github.com/robotframework/Selenium2Library)

8.Install Appium library (Install Appium)[https://pypi.org/project/robotframework-appiumlibrary/]

`pip install robotframework-appiumlibrary`

9.Install Appium for desktop [Download Link](https://github.com/appium/appium-desktop/releases/tag/v1.10.0)

10.Download Android SDK tools [link](http://www.androiddocs.com/sdk/index.html#Other)
-Download zip file
-extract folder
-add path till "Platform-tools" to path environment variable
-add folder path to ANDROID_HOME envisroment variable
-Open SDK Manager for folder install SDK's 

11.Enable Developer options in your real device and on the USB debugging

12.Connect device
[Guide to connect device](https://www.guru99.com/adb-connect.html) 

13.open command prompt and run below command to connected device id
`adb devices`

## Locate elements in Appium
You can write locators by inspecting elements in UIAutomator
[Video link](https://www.youtube.com/watch?v=MpY08mJi7NA)
[Documentation](https://developer.android.com/training/testing/ui-automator)

## Find appActivity and appPackage name of your app 
[Guide to get appActivity and addPackage](http://www.automationtestinghub.com/apppackage-and-appactivity-name/)
To open uiautomator enter below command in command prompt
`
uiautomator
`

