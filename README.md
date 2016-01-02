Welcome to the cocos2d-x installing guide!

# Installing on Windows

### [Download and install Cocos2d-x and Cocos from official site](http://www.cocos2d-x.org/download)

Cocos2d-x is for developing only. Cocos(Studio) is for designing mostly. I recommend both so you need to click "Cocos for Mac/Win with framework" download button (they are both included).

### [Download and install Python 2.7](https://www.python.org/downloads/)

> `IMPORTANT` You don't need that if you have chosen "Cocos for Mac/Win with framework". It's already included.

It's very important to install 2.7.x version and not 3+. It's also important to add python.exe to Path:

![It's important to add python.exe to Path](http://i.imgur.com/D96Uwr7.png)

### [Install common tools for Visual C++](https://www.visualstudio.com/products/visual-studio-community-vs)

That's minimal requirements for compiling cocos2d-x games for Windows:

![Common Tools for Visual C++ 2015](http://i.imgur.com/FaX9dBP.png)

You can use it for free forever but you must sign in at first start (microsoft account is free too). You will see something like this:

![Visual Studio Community 2015 Personal Account Info](http://i.imgur.com/0SVSKre.png)

Otherwise, you will be able to compile projects for windows only 30 days. I recommend you to sign in at once.

### If you plan to compile .apk for Android

I recommend to install following things to "C:\Cocos\tools", cause of Cocos Studio uses this path by default for Python (although it's not necessary).

#### [Download and install NDK](http://developer.android.com/ndk/downloads/index.html)

Download the latest version of the installer. Install it. Easy.

#### [Download and install JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html)

Download the latest version of the installer. Install it. Easy.

#### [Download and install SDK](http://developer.android.com/sdk/index.html)

Scroll down to "Other Download Options" > "SDK Tools Only". Download the latest version of the installer. Unzip it to somewhere (remember that I recommend "C:\Cocos\tools"?). Using Android SDK Manager install some packages:

* Android SDK Platform-tools
* Android SDK Build-tools
* SDK Platform of which version you plan to compile for
* Important things lying beside SDK Platform like "System Image" and other shit (not sure about how much it's needed)
* Android Support Library
* Google USB Driver (that's the best one... for running apps on your phone on the fly through USB)

The result must be something like this:

![Android SDK Manager Gentlement's Set](http://i.imgur.com/mbkEzle.png)

# Creating/running/compiling a project with Cocos Studio

Start the Cocos Studio (finally!).

## Setting up some preferences

Go to "Edit" > "Preferences" > "Platform".

You should see something like this:

![Preferences of Cocos Studio](http://i.imgur.com/UNTNMTJ.png?1)

If you are following my guide it's already installed. All that you need is to click "Browse..." and find all kinds of that shit (SDK, NDK, JDK).

To be continued...

# Creating/running/compiling a project with a console

To be continued...
