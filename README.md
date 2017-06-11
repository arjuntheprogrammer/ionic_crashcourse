
## IONIC2 Crash Course
https://www.youtube.com/watch?v=O2WiI9QrS5s

## Steps:
<ul>
<li> npm install -g ionic cordova</li>
<li> ionic start myApp</li>
<li>cd myApp</li>
<li>ionic lab</li>
</ul>

npm install -g ionic cordova

ionic serve //or// ionic lab //(to start)

ionic g page detail // creates new dir(page) automatically

cordova platform add android
cordova platform add ios

cordova platform ls


cordova run ios
cordova run android

export ANDROID_HOME=/home/arjun/android_sdk/Android/Sdk
export PATH=${PATH}:/home/arjun/android_sdk/Android/Sdk/platform-tools:/home/arjun/android_sdk/Android/Sdk/tools
