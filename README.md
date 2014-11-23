# Usage
* `git clone` this repo
* `rm -rf .git README.md` - delete unuseful files/folders
* Run `sbt` console and generate new project with `gen-android <platform-target> <package-name> <name>`
* Put plugin config inside `plugins-settings.sbt`
* Put project settings / build tasks etc. inside `build.sbt`
* After build changes and **Android Manifest file changes!**  console run `reload` (inside `sbt` console)



###Most useful commands inside `sbt` console:

* `gen-andrid` -> generate new project 
* `reload` -> reload .sbt build files without turning off idea sbt console 
* `clean` -> clean build
* `compile` -> compile project
* `android:package` -> package project ( ready for apk transfer )
*  without intellij : `android:install`, `android:run`, ...


### Requirements

* sbt version >= 13.5
