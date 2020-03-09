# ADB cheetsheet

##### Download apk from mobile

  - Search for apk name and path
```sh
adb shell pm list packages -f appname
```
  - Download apk
```sh
adb pull /data/app/com.app.name/*.apk
```
##### Start activity
```sh
am start -n "com.package.name/activity_name" -a intent_action -c intent_category
```
