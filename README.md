#NANS Project for Android
NANS (N-App N-Screen) project for Android is a modification of Android Framework which enables to launch and display multiple applications on multiple displays. The project aims to utilize resources on a smartphone which can connect multiple displays more efficently. Not only mirrors contents but also projects seperately on each display.  It is created by [RUBIS Lab](http://rubis.snu.ac.kr/researches?csrl=25780).
Currently NANS project supports Android 5.1.1, 5.0.1(Lollipop), 4.4.2 (KitKat) and 4.2.2 (Jelly Bean). 
This is Android 5.1.1(Lollipop) branch. 

## Video Demo
- "NANS Technology with In-Vehicle Infotainment System" 
[![Video Demo](https://github.com/rubis-lab/images/blob/master/NANS.Technology.with.In-Vehicle.Infotainment.System.PNG)](https://youtu.be/Y-TmMn7kuhU "N-App N-Screen Control on Android by SNU")

- "N-App N-Screen Control on Android by SNU"
[![Video Demo](https://github.com/rubis-lab/images/blob/master/N-App.N-Screen.Control.on.Android.PNG)](https://youtu.be/KTYCjc8aoMU "NANS Technology with In-Vehicle Infotainment System")

## Features
- Android-based mobile technology
- Supports voice control and external input control
- Supports Miracast / MHL-HDMI
- Supports external input devices, resolution adaptation and audio source change

####5.1.1 Lollipop Update
- Supports individual stacks for each display
- Supports Full HD Projection

## What we modified?
![NANS](https://github.com/rubis-lab/images/blob/master/NANS.Android.Modification.Parts.png)

## For Developers
Please be aware installing NANS Project requires to build the whole Android platform and flash it to a device. RUBIS Lab does not take any responsibility for results of flashing your device.
NANS Android consists of two parts: framework modification and client application for controling NANS. Before you download, you need to install 'Repo'. For information about downloading Android, please see https://source.android.com/source/downloading.html
To download NANS Android execute:

    repo init -u https://github.com/rubis/nans_project_for_android.git
    repo sync

For more information, please see https://github.com/rubis-lab/NANS_Project_for_Android/wiki.

## Licence
Our projects are released under [Apache 2.0 Licence] (http://www.apache.org/licenses/LICENSE-2.0.html).
* https://github.com/rubis-lab/NANS_Project_for_Android 
* https://github.com/rubis-lab/NANS_frameworks_base
* https://github.com/rubis-lab/NANS_frameworks_native
* https://github.com/rubis-lab/NANS_packages_apps_settings
* https://github.com/rubis-lab/NANS_hardware_libhardware_legacy

## Community
You can ask questions or suggestions on our google group: 
https://groups.google.com/forum/#!forum/n-app-n-screen-android
You may contact Ohchul Kwon <ockwon@rubis.snu.ac.kr> for any questions you may have or bugs that you find.

## Developers
- Ohchul Kwon <ockwon@rubis.snu.ac.kr>
- Hwansuk Choi <hschoi@rubis.snu.ac.kr>
- Daechul Park <dcpark@rubis.snu.ac.kr>
- Chang-Gun Lee <cglee@snu.ac.kr>

## About RUBIS Lab.
RUBIS Lab. is a "Real-time UBiquitous Systems Laboratory" at Seoul National Univercity, Korea.
We are researching and developing technologies in embedded systems such as smartphones and ECUs.
Webpage: http://rubis.snu.ac.kr
