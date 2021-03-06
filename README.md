# OVERVIEW
-----

 What is beacon?
---------------
View this video first https://www.youtube.com/watch?v=dpSGbWxjQNw

Beacons are permanently sending out their unique identifier to notify nearby smartphones of their existence, hence the name beacons. A compatible app running on the smartphone then knows that it is in a close proximity. Depending on the application, this can trigger an action on the smartphone, e.g. displaying some information about nearby items.

Beacons are available in different sizes and shapes and from different vendors, like this one

![ScreenShot](http://3.bp.blogspot.com/-2WhxB_Pur9Q/U1Ph5FFuA9I/AAAAAAAAAG4/dM55P_bD26g/s1600/beacon.png)

 Is beacon work with Iphone and Android devices?
--------------
Yes but they work differently.
Only devices from IOS7 above will always scan Bluetooth Low Enery (BLE) and active related apps when it in the area of beacons in system operating level (although the app is closed). 
For Android devices there is no beacon system at operating level so must have a beacon app running in device at least is in background level and need to scan BLE to find and interact with beacons. And because android devices need to scan beacon at application level so it mean will costs energy.

 Bluetooth Low Energy (BLE) / Bluetooth Smart
---------------
Bluetooth Low Energy is also known as Bluetooth Smart. Since Android 4.3 Jelly Bean, Android also supports Bluetooth Smart.
Android Smartphone Requirements:

    1. Android > 4.3
    2. Bluetooth Smart radio unit

The Android SDK has no built-in support for beacons. But there is a library from [Radius-Networks] (http://www.radiusnetworks.com/) that can be used.   

[How BLE work?] (http://www.warski.org/blog/2014/01/how-ibeacons-work/)

 Beacon Advertisements
---------------
Beacons broadcast in regular intervals. They send out their ID and ID consist three part (see image):

    1. UUID (organization or company)
    2. major (arbitrarily, e.g. specific chain store)
    3. minor (e.g. location in store)
	
![ScreenShot] (http://www.codemag.com/Article/Image/1405051/image2.png)
![ScreenShot](http://blog.reco2.me/wp-content/uploads/2015/01/Bluetooth-Beacon-How-Infographic.jpg)
![ScreenShot](http://image.slidesharecdn.com/aretailersguidetoibeaconmarketingdeckkkdmms-140409102017-phpapp01/95/a-retailers-guide-to-ibeacon-marketing-37-638.jpg?cb=1397038906)


Demo 
---------------
You can buy an beacon or [turn your mac into a beacon] (http://beekn.net/2013/11/turn-your-mac-into-a-bluetooth-beacon/) or iphone, ipad also. 
Unfortunately, I don't have any beacons or mac now :( . Make sure you have devices support for Bluetooth LE or you can't test this. Zenfone 5 is will be OK. So keep calm and stay turn! Below image is my tablet do not support for bluetooth LE so my app didn't work.

![ScreenShot] (https://dl.dropboxusercontent.com/s/tisa82l8nag8gu6/Screenshot_2015-06-01-18-46-11.png)

Reference 	
---------------
[Develop an iBeacons App] (http://beekn.net/developing-ibeacon-app/)

