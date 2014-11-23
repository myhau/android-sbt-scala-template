# Usage

* Generate project with sbt gen-android
* Put plugin config inside plugins-settings.sbt
* Put project settings / build tasks etc. inside build.sbt


# Requirements 

* [android-sdk-scala] (https://github.com/pfn/android-sdk-plugin) as a global sbt plugin.


### Most useful commands

* sbt 
* sbt gen-andrid -> generate new project ( you must have [android-sdk-scala] (https://github.com/pfn/android-sdk-plugin) as global plugin )
* sbt reload -> reload .sbt build files without truning off idea sbt console 
* sbt compile -> compile project
* sbt android:package -> package project ( ready for apk transfer )





