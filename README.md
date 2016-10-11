# tun2socks-demo-app

Pre-requisites:
* cordova
* Android Studio (Android SDK, gradle). 

Run instructions:
* Add Android platform:
`cordova platform add android`
* Remove tun2socks plugin (if already installed, to rebuild):
`cordova plugin rm cordova-plugin-tun2socks`
* Add tun2socks plugin
`cordova plugin add <path_or_url_to_tun2socks_plugin>`
* Build:
`cordova build`
* Install:
`adb install -r <path_to_apk>`

