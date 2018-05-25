# chimera

[![Greenkeeper badge](https://badges.greenkeeper.io/Thram/chimera.svg)](https://greenkeeper.io/)

Cordova/Crosswalk boilerplate for Hybrid Apps

### Follow this basic steps to install Cordova and the Crosswalk Plugin: 
https://crosswalk-project.org/documentation/cordova/cordova_4.html

### For more plugins check:
https://cordova.apache.org/plugins/

http://ngcordova.com/docs/plugins/ (For AngularJS Projects) 


---

## Just copy your Web App into the "www" folder and run:

### For emulation

cordova emulate android
cordova emulate ios

### For running into devices

cordova run android --device
cordova run ios --device

### For build 

cordova build android 

This will create 2 APKs for both X86 and ARM architectures.

./platforms/android/build/outputs/apk/android-x86-debug.apk
./platforms/android/build/outputs/apk/android-armv7-debug.apk

cordova build ios

#### For release files add the "--device" flag: cordova build android --device

## Recomended JS Frameworks for Hybrid Apps

Frameworks7 (Android Material and iOS): http://www.idangero.us/framework7/
