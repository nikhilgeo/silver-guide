Start activity
am start -n "com.package.name/activity_name" -a intent_action -c intent_category 

Download apk from mobile device
Filter the apk and list:
adb shell pm list packages -f appname
Download the apk
adb pull /data/app/*.apk
