Calabash-Android Test Project
=============================


This project is intented to help you verify your Calabash-Android installation on a very simple apk.


We will assume that you already installed Calabash-Android. (Instructions are [here](https://github.com/calabash/calabash-android/))


* Clone this project

* Build project
    * Import the project into Eclipse
    * Run the demo app on your device or emulator

* Configure calabash-android
    * In a terminal go to `<project-path>/calabash`
    * Run `calabash-android setup` and answer the questions
        * Package name: `sh.calaba.demoproject`
        * Fully qualified name of main activity: `sh.calaba.demoproject.AndroidDemoProjectActivity`
        * Path to app: `<project-path>/bin/AndroidDemoProject.apk`
        * Api level: Pick 8 or above (for now)
        * When asked about specifying a keystore select `n`
    * Run `calabash-android build` to build the test server
    * Run `calabash-android run` to run the single feature that comes with the demo project