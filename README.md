# ezar-compass
Augmented reality compass using ezAR plugins for Cordova

![](http://static1.squarespace.com/static/54d524d4e4b0f489aba79ed2/55310535e4b03253914c8657/55310564e4b086967b6ed7fb/1429276278307/ezar-compass.png)
##Getting Started
While ezAR works with Cordova-based SDKs such as Ionic, this example uses Cordova CLI examples are provided below. 
Install or update your [Apache Cordova sdk](https://cordova.apache.org/)

step-0.  Download and unzip the ezAR Startup Kit (ver 0.2 or greater) from [ezartech.com](http://ezartech.com

*Note: the project will automatically install its required plugins. The Cordova 
whitelist and device-orientation plugins will be installed from npm. The 
ezAR VideoOverlay and  Snapshot plugins will be installed from the relative path 
../../plugins/ directory. If the ezAR plugins are not at that location please 
edit the config.xml with the proper location of the plugins.*

step-1.  Add your target platform(s) to the project

        cordova platform add ios
    
or

        cordova platform add android


step-2.  Build and install on device

*Note: because of the ezAR camera requirement the app will only perform correctly 
when installed on a real mobile device.*

##ezAR Docs and Tech Support
See [ezartech.com](http://ezartech.com) for documentation and support.


Copyright (c) 2015-2016, ezAR Technologies