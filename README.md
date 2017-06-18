This is a starter template for [Ionic](http://ionicframework.com/docs/) projects.

## How to develop application template

```
ionic start ionic-google-maps-example blank
cd ionic-google-maps-example/
ionic cordova plugin add cordova-plugin-googlemaps --variable API_KEY_FOR_ANDROID="AIzaSyCrBTxRRlEFSP4k-d0h3_KlKLVPUYGu5Aw" --variable API_KEY_FOR_IOS="AIzaSyAyRXixj-Xjh2X8MNXNN9Ygkun-_pdOhkk"
npm install --save @ionic-native/google-maps
npm install @types/google-maps --save
``` 

## How to run this application in IOS
```bash
$ ionic cordova platform add ios
$ ionic cordova run ios
```

Substitute ios for android if not on a Mac.

## Codes 
See git history to learn how to implement google maps.

!["Git History](git_history.png)

