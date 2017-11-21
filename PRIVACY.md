# FACEGROK PRIVACY

This privacy document concerns the software application FaceGrok 
(“Application”) for mobile devices.  This document's primary purpose is to 
inform you of potential tracking by certain third-parties in versions of 
Application distributed via Google Play.

All versions of Application load code from these sources:

* [FaceDetector](http://dl.bintray.com/fotoapparat/fotoapparat)
* [JitPack](https://jitpack.io)


## Versions 1.3 or earlier

Application versions contained in this repository (1.3 or earlier) do not 
contain any trackers and  ask for camera permissions and access to storage:

* [android.permission.CAMERA](http://androidpermissions.com/permission/android.permission.CAMERA)
* [android.permission.READ_EXTERNAL_STORAGE](http://androidpermissions.com/permission/android.permission.READ_EXTERNAL_STORAGE)
* [android.permission.WRITE_EXTERNAL_STORAGE](http://androidpermissions.com/permission/android.permission.WRITE_EXTERNAL_STORAGE)

## Versions 1.4 or later

Application versions in Google Play as of November 21, 2017 (versions 1.4 
or later) contain the signatures of these trackers:

* [AppsFlyer](https://support.appsflyer.com/hc/en-us/articles/207032126-AppsFlyer-SDK-Integration-Android)
* [AppNexus](https://wiki.appnexus.com/display/sdk/Integrate+the+SDK#IntegratetheSDK-Android)
* [Flurry](https://developer.yahoo.com/flurry/docs/integrateflurry/android/)
* [HockeyApp](https://support.hockeyapp.net/kb/client-integration-android/hockeyapp-for-android-sdk)
* [Leanplum](https://www.leanplum.com/docs/android/setup#install-the-sdk)

Application was modified to add tracker signatures, but code for that 
version is not available here.  Application does not initialize trackers 
or contain any real API keys.  Application versions 1.4 and up ask for 
these permissions:

* [android.permission.CAMERA](http://androidpermissions.com/permission/android.permission.CAMERA)
* [android.permission.INTERNET](http://androidpermissions.com/permission/android.permission.INTERNET)
* [android.permission.ACCESS_NETWORK_STATE](http://androidpermissions.com/permission/android.permissionACCESS_NETWORK_STATE
* [android.permission.ACCESS_WIFI_STATE](http://androidpermissions.com/permission/android.permissionACCESS_WIFI_STATE
* [android.permission.READ_PHONE_STATE](http://androidpermissions.com/permission/android.permission.READ_PHONE_STATE)
* [android.permission.READ_EXTERNAL_STORAGE](http://androidpermissions.com/permission/android.permission.READ_EXTERNAL_STORAGE)
* [android.permission.WRITE_EXTERNAL_STORAGE](http://androidpermissions.com/permission/android.permission.WRITE_EXTERNAL_STORAGE)
* [android.permission.GET_ACCOUNTS](http://androidpermissions.com/permission/android.permission.GET_ACCOUNTS)
* [android.permission.WAKE_LOCK](http://androidpermissions.com/permission/android.permission.WAKE_LOCK)
* [android.permission.ACCESS_FINE_LOCATION](http://androidpermissions.com/permission/android.permission.ACCESS_FINE_LOCATION)
* [android.permission.ACCESS_COARSE_LOCATION](http://androidpermissions.com/permission/android.permission.ACCESS_COARSE_LOCATION)

Application versions 1.4 and up also load code from Google, including 
[Google Cloud Messaging](https://developers.google.com/cloud-messaging/gcm).


# Contact
If you have any questions regarding privacy while using the Application, 
or have questions about our practices, please contact the author.

