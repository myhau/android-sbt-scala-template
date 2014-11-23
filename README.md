# Usage
* `git clone` this repo
* `rm -rf .git README.md` - delete unuseful files/folders
* Generate project with `sbt "gen-android <platform-target> <package-name> <name>"`
* Put plugin config inside `plugins-settings.sbt`
* Put project settings / build tasks etc. inside `build.sbt`

### Most useful commands

* `sbt` 
* `sbt gen-andrid` -> generate new project ( you must have [android-sdk-scala] (https://github.com/pfn/android-sdk-plugin) as global plugin )
* `sbt reload` -> reload .sbt build files without turning off idea sbt console 
* `sbt clean` -> clean build
* `sbt compile` -> compile project
* `sbt android:package` -> package project ( ready for apk transfer )


### Requirements

* sbt version >= 13.5
