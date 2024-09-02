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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://hardware-updates.techidaily.com/effortless-setup-targus-dock-compatibility-download-and-install-drivers-in-a-flash/"><u>[EFFORTLESS SETUP] Targus Dock Compatibility: Download & Install Drivers in a Flash!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-unlock-advanced-features-of-obs-studio-on-android-platforms/"><u>[New] 2024 Approved  Unlock Advanced Features of OBS Studio on Android Platforms</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-cutting-edge-chrome-vocal-transforming-apps-top-5-choices-for-2024/"><u>[New] Cutting-Edge Chrome Vocal Transforming Apps  Top 5 Choices for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-footage-to-frame-crafting-youtube-thumbnails-on-mobile-devices-for-2024/"><u>[New] From Footage to Frame  Crafting YouTube Thumbnails on Mobile Devices for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-innovations-for-crafting-striking-fb-video-ads/"><u>[New] In 2024, Innovations for Crafting Striking FB Video Ads</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-screen-to-streamer-effortlessly-reviewed/"><u>[New] In 2024, Screen to Streamer, Effortlessly Reviewed</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unbeatable-deal-get-top-quality-discord-icons-free-for-2024/"><u>[New] Unbeatable Deal  Get Top-Quality Discord Icons FREE for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/secure-now/"><u>[Secure Now!]</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-creation-to-consumption-igtv-vs-youtube-explained-for-you-for-2024/"><u>[Updated] From Creation to Consumption  IGTV Vs. YouTube Explained for You for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-elevating-your-visuals-mastering-instagram-edits-in-fcpx/"><u>[Updated] In 2024, Elevating Your Visuals  Mastering Instagram Edits in FCPX</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-find-your-perfect-game-recorder-top-10-free-apps/"><u>[Updated] In 2024, Find Your Perfect Game Recorder  Top 10 Free Apps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/apples-upcoming-household-helper-potential-launch-date-and-pricing-details-unveiled/"><u>Apple's Upcoming Household Helper: Potential Launch Date & Pricing Details Unveiled!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/beyond-power-fluctuations-leaked-documents-reveal-ongoebling-cpu-instability-at-intel/"><u>Beyond Power Fluctuations: Leaked Documents Reveal Ongoebling CPU Instability at Intel</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-a-cash-flow-career-with-content-creation-like-ajey-nagar/"><u>Crafting a Cash-Flow Career with Content Creation Like Ajey Nagar</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-asrock-ab350-pro4-windows-drivers-complimentary-access-and-easy-setup-tips/"><u>Download ASRock AB350 Pro4 Windows Drivers - Complimentary Access and Easy Setup Tips</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-now-enhance-your-corsair-mouse-with-the-latest-software-update/"><u>Download Now: Enhance Your Corsair Mouse with the Latest Software Update</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722960089918-downloadupdate-your-surface-device-drivers-with-simple-steps/"><u>Download/Update Your Surface Device Drivers with Simple Steps!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-download-ultimate-intel-usb-30-driver-package-for-windows-10/"><u>Free Download: Ultimate Intel USB 3.0 Driver Package for Windows 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-best-audio-experience-installing-soundmax-drivers-on-windows-systems/"><u>Get The Best Audio Experience: Installing SoundMAX Drivers on Windows Systems</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-hp-officejet-pro-8600-drivers-compatible-with-windows-os/"><u>Get the Latest HP Officejet Pro 8600 Drivers Compatible with Windows OS</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722977880361-get-the-most-recent-canon-mp250-printer-driver-free-software-downloads-available-now/"><u>Get the Most Recent Canon MP250 Printer Driver - Free Software Downloads Available Now</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-software-update-for-your-corsair-h80i-v2-cooling-system/"><u>Get the Newest Software Update for Your Corsair H80i V2 Cooling System</u></a></li>
<li><a href="https://techidaily.com/handling-chromes-security-warning-on-file-downloads-steps-to-successfully-save-files/"><u>Handling Chrome's Security Warning on File Downloads: Steps to Successfully Save Files</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-download-and-update-razers-naga-gaming-mouse-drivers-for-windows-computers/"><u>How to Download and Update Razer's Naga Gaming Mouse Drivers for Windows Computers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-ensure-optimal-performance-of-lenovo-ideapad-100-by-updating-drivers-on-windows-10/"><u>How To Ensure Optimal Performance of Lenovo IdeaPad 100 by Updating Drivers on Windows 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-newest-mpow-bluetooth-drivers-on-your-windows-pc-windows-1187/"><u>How to Get the Newest MPOW Bluetooth Drivers on Your Windows PC (Windows 11/8/7)</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-keep-your-acer-nitro-5-at-its-best-essential-driver-upgrades-explained/"><u>How to Keep Your Acer Nitro 5 at Its Best - Essential Driver Upgrades Explained</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-update-epson-perfection-v500-with-new-drivers-grab-them-here/"><u>How to Update Epson Perfection V500 with New Drivers – Grab Them Here!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-update-your-xbox-360-controller-with-the-latest-software-drivers/"><u>How to Update Your Xbox 360 Controller with the Latest Software Drivers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-deskjet-2600-windows-drivers-compatible-versions-for-os-7-8-and-10/"><u>HP DeskJet 2600 Windows Drivers: Compatible Versions for OS 7, 8 & 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-officejet-pro-cu8610-driver-software-downloads-for-multiple-windows-versions/"><u>HP Officejet Pro Cu8610 Driver Software Downloads for Multiple Windows Versions</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-best-ispoofer-alternative-to-try-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, The Best iSpoofer Alternative to Try On Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-the-ipogo-get-you-banned-and-how-to-solve-it-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>In 2024, Will the iPogo Get You Banned and How to Solve It On Apple iPhone XR | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-your-brother-hl-l2380dw-on-windows-with-this-free-print-driver/"><u>Install Your Brother HL-L2380DW on Windows with This Free Print Driver</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-version-of-canoscan-lide-220-software-with-improved-features/"><u>Latest Version of Canoscan LiDE 220 Software with Improved Features</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/lenovo-thinkpad-t450-how-to-quick-and-secure-driver-update-guide/"><u>Lenovo ThinkPad T450 How-To: Quick & Secure Driver Update Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/logitech-g203-webcam-driver-download-for-windows-users-latest-versions-included/"><u>Logitech G203 Webcam Driver Download for Windows Users: Latest Versions Included</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/masters-choice-top-10-precision-tools-for-downloading-vimeo-files/"><u>Master's Choice  Top 10 Precision Tools for Downloading Vimeo Files</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-lexar-connections-with-fast-downloads-of-usb-drivers/"><u>Mastering Lexar Connections with Fast Downloads of USB Drivers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-quick-driver-revisions-a-guide-to-enhancing-synaptics-ps2-touchpads/"><u>Mastering Quick Driver Revisions: A Guide to Enhancing Synaptics PS/2 Touchpads</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-technology-a-deep-dive-into-toms-hardware-findings/"><u>Mastering Technology: A Deep Dive Into Tom's Hardware Findings</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/new-year-language-learning-goal/"><u>New Year, Language Learning Goal</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ready-set-race-grab-the-top-z270-carbon-drivers-today/"><u>Ready, Set, Race? Grab the Top Z270 Carbon Drivers Today</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/steelseries-arctis-5-driver-setup-guide-free-download-and-easy-installation/"><u>SteelSeries Arctis 5 Driver Setup Guide: Free Download and Easy Installation</u></a></li>
<li><a href="https://screen-capture.techidaily.com/step-by-step-audio-preservation-in-the-digital-age/"><u>Step-by-Step Audio Preservation in the Digital Age</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/the-complete-guide-to-canon-eos-driver-updates-and-free-downloads/"><u>The Complete Guide to Canon EOS Driver Updates and Free Downloads</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/update-your-canon-mg3000-printer-drivers-step-by-step-guide/"><u>Update Your Canon MG3000 Printer Drivers - Step by Step Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/update-your-graphics-card-download-rtx-2080-super-drivers-compatible-with-windows-11/"><u>Update Your Graphics Card - Download RTX 2080 Super Drivers Compatible with Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-let-us-talk-about-the-famous-photoshop-and-most-commonly-used-glitch-effect-the-article-understudy-will-discuss-in-detail-about-photo-glitch-effect-/"><u>Updated Let Us Talk About the Famous Photoshop and Most Commonly Used Glitch Effect. The Article Understudy Will Discuss in Detail About Photo Glitch Effect for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722965022116-whats-new-upgraded-software-for-the-logitech-extreme-3d-controller/"><u>What's New? Upgraded Software for the Logitech Extreme 3D Controller</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722961553338-win-7-network-adapter-challenges-heres-how-you-can-resolve-them-easily/"><u>Win 7 Network Adapter Challenges? Here's How You Can Resolve Them Easily</u></a></li>
</ul></div>
