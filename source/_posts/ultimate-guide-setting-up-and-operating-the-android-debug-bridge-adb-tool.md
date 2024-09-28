---
title: "Ultimate Guide: Setting Up & Operating the Android Debug Bridge (ADB) Tool"
date: 2024-09-01T05:44:18.930Z
updated: 2024-09-02T05:44:18.930Z
tags:
  - android
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e90a41374ab8bcea029035e600ef5fff009cee16ec9e8eead9f3969598aefde0.jpg
---

## Ultimate Guide: Setting Up & Operating the Android Debug Bridge (ADB) Tool

### Quick Links

* [Step One: Download Platform Tools](https://snapchat-videos.techidaily.com/updated-mastering-access-to-exclusive-snapshots-for-2024/)
* [Step Two: Enable USB Debugging on Your Phone](https://facebook-video-footage.techidaily.com/new-2024-approved-chuckle-filled-chapters-best-comedy-video-plans-in-a-nutshell/)
* [Step Three: Test ADB and Install Your Phone's Drivers (if Needed)](https://www.howtogeek.com/125769/how-to-install-and-use-abd-the-android-debug-bridge-utility/#step-three-test-adb-and-install-your-phone-s-drivers-if-needed)
* [Step Four (Optional): Add ADB to Your System PATH](https://www.howtogeek.com/125769/how-to-install-and-use-abd-the-android-debug-bridge-utility/#step-four-optional-add-adb-to-your-system-path)
* [Useful ADB Commands](https://article-posts.techidaily.com/new-leading-list-elite-call-alert-engineers/)

### Key Takeaways

 To install and use Android Debug Bridge Utility (ADB), download the platform tools from the ADB page and extract them anywhere. Open the Settings app on your phone, go to the "System" page, tap the build button seven times, and connect your phone to your PC. Open PowerShell, navigate to the platform tools folder, then run any adb command.

 ADB, Android Debug Bridge, is a command-line utility included with Google's Android SDK. ADB can control your device over USB from a computer, copy files back and forth, install and uninstall apps, run shell commands, and more.

 We've covered some other tricks that require ADB in the past, including [backing up and restoring your smartphone or tablet](https://buynow-reviews.techidaily.com/logitech-c615-camera-assessment-balancing-cost-effectiveness-with-high-functionality/) and [installing Android apps to your SD card by default](https://facebook-record-videos.techidaily.com/new-2024-approved-epic-battle-royale-thumbnails-done-fast/). ADB is used for a variety of geeky Android tricks.

##  Step One: Download Platform Tools

![Download Platform Tools.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/2021-10-28_13-03-40.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
 Head to the [Android SDK Platform Tools download page.](https://developer.android.com/studio/releases/platform-tools) Select the link for your operating system from the "Downloads" section. This will download a ZIP file, which you can unzip wherever you want to store the ADB files--they're portable, so you can put them anywhere you want.

 That's all we have to do for now. Just make sure to remember where you unzipped the files, we will need to access that later.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Step Two: Enable USB Debugging on Your Phone

 To use ADB with your Android device, you must [enable a feature called "USB Debugging."](https://desktop-recording.techidaily.com/premium-video-capture-without-extras-for-2024/) Open your phone's app drawer, tap the Settings icon, and select "About Phone". Scroll all the way down and tap the "Build Number" item seven times. You should get a message saying you are now a developer.

 Head back to the main Settings page, and you should see a new option in the "System" section called "Developer Options." Open that, and enable "USB Debugging."

![Enable USB Debugging.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/Screenshot_20211028-130124.png) 

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Later on, when you connect your phone to your computer, you'll see a popup entitled "Allow USB Debugging?" on your phone. Check the "Always allow from this computer" box and tap OK.

##  Step Three: Test ADB and Install Your Phone's Drivers (if Needed)

 Open the Command Prompt (PowerShell and Terminal will also work) and change the directory to where you unzipped the file earlier. You can do this by entering the command below. Replace the file destination with your own:

 CD C:\\"Program Files"\\platform-tools

 To test whether ADB is working properly, connect your Android device to your computer using a USB cable and run the following command:

adb devices

 If you're using PowerShell or the Terminal with a PowerShell profile, you'll need to run `./adb devices` instead.

![Run &quot;.\adb devices&quot; to list connected Android phones.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/ADB-debug.png) 

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 You should see a device in the list. If your device is connected but nothing appears in the list, you'll need to install the appropriate drivers.

 In the vast majority of cases, your PC will automatically detect your phone and set it up with the appropriate drivers. If that doesn't happen, you can usually find the drivers for your device from the [XDA Developers](http://forum.xda-developers.com/) forums or your manufacturer's website. The drivers for Google devices, like Pixel phones, can be [found on Google's website](https://developer.android.com/studio/run/win-usb). Google also has [a list of USB drivers sorted by manufacturer](https://developer.android.com/studio/run/oem-usb) that will save you a ton of time.

 Make sure to carefully follow the instructions for installing your device's drivers if specific instructions are provided. 

 If you download the drivers manually, you may have to force Windows to find them on your device. Open the Device Manager (click Start, type "Device Manager", and press Enter), locate your device, right-click it, and select Properties. You may see a yellow exclamation mark next to the device if its driver isn't installed properly.

![Open &quot;Portable Devices,&quot; then right-click your phone and click &quot;Properties.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/properties.png) 

 On the Driver tab, click "Update Driver."

![Open the &quot;Drive&quot; tab, then click &quot;Update Driver.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/tab-then-update.png) 

 Use the Browse my computer for driver software option.

![Click &quot;Browse My Computer For Drivers.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/manually-browse.png) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
 Find the drivers you downloaded for your device.

![Browse to the local drivers, tick &quot;Include Subfolders,&quot; then click &quot;Next&quot; to install the drivers manually.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/10/1-2-3.png) 

 If you downloaded the drivers from your OEM or Google, look for an executable or INF file in the drivers folder. 

 Once you've installed your device's drivers, plug in your phone and try the adb devices command again:

adb devices

 Or:

./adb devices

 If all went well, you should see your device in the list, and you are ready to start using ADB!

 If running `adb devices` still won't return any devices, there are a few things you can try:

* Swap out your USB cable for a higher quality one
* Plug the USB cable into a different port
* Plug the USB cable directly into the USB ports on your motherboard (at the back), rather than the ports on the front of your PC or on a USB hub.
* Change your phone's USB mode to PTP, MTP (File Transfer/Android Auto), or USB Tethering.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Step Four (Optional): Add ADB to Your System PATH

 As it stands, you have to navigate to ADB's folder and open a Command Prompt there whenever you want to use it. However, if you add it to your Windows System PATH, that won't be necessary--you can just type `adb` from the Command Prompt to run commands whenever you want, no matter what folder you're in.

 The process is a bit different on Windows 11, 10, and 7, so [check out our full guide to editing your System PATH](https://android-frp.techidaily.com/in-2024-the-complete-guide-to-meizu-frp-bypass-everything-you-need-to-know-by-drfone-android/) for the steps required to do this.

Related: [How to Edit Your System PATH for Easy Command Line Access in Windows](https://android-frp.techidaily.com/in-2024-the-complete-guide-to-meizu-frp-bypass-everything-you-need-to-know-by-drfone-android/) 

##  Useful ADB Commands

 In addition to the variety of tricks that require ADB, ADB offers some useful commands:

* **adb install C:\\package.apk** \--- Installs the package located at C:\\package.apk on your computer on your device.
* **adb uninstall package.name** \--- Uninstalls the package with package.name from your device. For example, you'd use the name com.rovio.angrybirds to uninstall the Angry Birds app.
* **adb push C:\\file /sdcard/file** \--- Pushes a file from your computer to your device. For example, the command here pushes the file located at C:\\file on your computer to /sdcard/file on your device
* **adb pull /sdcard/file C:\\file** \--- Pulls a file from your device to your computer -- works like adb push, but in reverse.
* **adb logcat** \--- View your Android device's log. Can be useful for debugging apps.
* **adb shell** \--- Gives you an interactive Linux command-line shell on your device.
* **adb shell command** \--- Runs the specified shell command on your device.

---

 For a full guide to ADB, consult the [Android Debug Bridge page](http://developer.android.com/tools/help/adb.html) on Google's Android Developers site.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


