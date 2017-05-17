#Appodeal Cordova Plugin

This is an official Appodeal Cordova plugin, created to support Appodeal SDK with Apache Cordova.

##SDK
[![](https://img.shields.io/badge/docs-android-green.svg)](http://www.appodeal.com/sdk/documentation?framework=9&full=1&platform=1)
[![](https://img.shields.io/badge/docs-ios-green.svg)](http://www.appodeal.com/sdk/documentation?framework=9&full=1&platform=2)

##Install

Simply go to the project folder over console/terminal and run there following command:

    cordova plugin add https://github.com/appodeal/appodeal-cordova-nodex-plugin.git  
     
This is a modification to the plugin.xml that allows appodeal to be used in conjunction 
with Cranberrygames Google Play Services, found here:
https://github.com/cranberrygame/cordova-plugin-game
      
Changelog:     
      
    <framework src="com.google.android.gms:play-services-ads:9+" />
    to:
    <framework src="com.google.android.gms:play-services-ads:+" />

