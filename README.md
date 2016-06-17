# adb-tools
Tools for complile, install and uninstall Android apps by Bourne shell commands

## Synopsis

adb-tools provides an alternative efficient way to build the Android apps by commands instead of using Android Studio SDK tools. 

## Code

These tools written by Bourne Shell in Ubuntu 14.04.

## Prerequisition Installation

In order to run these tools you would search the following utilities/tools exist in your system or install them if not.
* Android Studio
* adb
* awk
* bash
* gradlew

You probably need to use whereis command to check the utility existence. 
eg. whereis adb

## Test and Run
1. copy the tools from bin to your local directory and change the mode to 755 for each of them
2. export your local directory so these tools are executable. eg. export PATH="$PATH:/your directory"
3. change directory to the Android project. eg. cd ~/android/dev/MyAPP
4. compile/run the app: adb-run
5. install the apk to your mobile: adb-install
6. uninstall the app in your mobile: adb-uninstall

## Contributors

Let people know how they can dive into the project, include important links to things like issue trackers, irc, twitter accounts if applicable.

## License

A short snippet describing the license (MIT, Apache, etc.)
