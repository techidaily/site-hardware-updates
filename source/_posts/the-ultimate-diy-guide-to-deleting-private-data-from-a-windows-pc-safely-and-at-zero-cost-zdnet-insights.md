---
title: The Ultimate DIY Guide to Deleting Private Data From a Windows PC Safely and at Zero Cost - ZDNET Insights
date: 2024-11-11T16:06:24.717Z
updated: 2024-11-17T23:03:53.803Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3546fd9956a8b6a73b831712e52723669b090c846a7d2596697ef888fa555dd7.jpg
---

## Securely Erase Sensitive Information From Your Windows PC: A Step-by-Step Guide to Protecting Privacy Without Cost - Insights

![delete key on keyboard](https://www.zdnet.com/a/img/resize/d63e45ef5eb131dc96ab27bda73125ed344a82c5/2024/09/29/d681f9f6-c785-48e5-b76d-2d11b529a893/gettyimages-172972238.jpg?auto=webp&width=1280)

monkeypics/Getty Images

When you replace your old but still functional Windows PC with a shiny new model, you have several options for that gently used device. You can give it away to a friend or family member. You can donate it to a charitable organization like Goodwill (which partners with [Dell Reconnect](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fwww.dell.com%2Fen-us%2Fdt%2Fcorporate%2Fsocial-impact%2Fadvancing-sustainability%2Fhow-to-recycle%2Ffaq.htm%23tab0%3D1)). You can even trade it in for credit or sell it on a third-party site like [Swappa](https://swappa.com/sell/laptop) or [Back Market](https://www.awin1.com/awclick.php?mid=18275&id=423585&clickref=zd-%5F%5FCOM%5FCLICK%5FID%5F%5F-dtp&ued=https%3A%2F%2Fwww.backmarket.com%2Fen-us%2Fbuyback%2Fhome). 

**Also: [Microsoft to start charging for Windows 10 updates next year. Here's how much](https://www.zdnet.com/article/microsoft-to-start-charging-for-windows-10-updates-next-year-heres-how-much/)**

Whichever course of action you take, though, your most important task is to **_permanently delete all your personal files_** from that PC before you pass it along. With a desktop PC, that might be as easy as swapping out the system drive for a new one. But that's usually not an option with a laptop, where replacing storage can be impossible or prohibitively expensive. 

For laptops and for desktops where you aren't replacing the system drive, the simplest route is to reset the PC, choosing the option to remove personal files and reinstall Windows. On a PC running Windows 10, go to Settings > Update & Security > Recovery. On a Windows 11 device, the Reset PC option is under Settings > System > Recovery. Make sure you choose the Remove Everything option, as shown here.

When you're resetting a PC to give away or sell, be sure to choose the Remove Everything option.

Screenshot by Ed Bott/ZDNET

It takes several prompts before you get to the actual reset option (you don't want to do this accidentally, after all) and if you dig through the settings you can find a Clean Disk option designed to remove all data in addition to removing your files. As an alternative, you can boot from Windows installation media, remove all existing disk partitions, and then perform a clean install.

Either option removes existing personal files, but Microsoft's documentation cautions that "the data erasure functionality is targeted at consumers and does not meet government and industry data erasure standards." As a result, it's possible that someone with advanced technical skills could use forensic tools or data recovery software to access some of the deleted information.

**Also: [How to upgrade your 'incompatible' Windows 10 PC to Windows 11](https://www.zdnet.com/article/how-to-upgrade-your-incompatible-windows-10-pc-to-windows-11/)**

On modern systems with solid-state drives, you can often find a management utility that includes a Secure Erase command. For Samsung SSDs, use the [Samsung Magician](https://shop-links.co/link/?exclusive=1&publisher_slug=itechdaily19598&url=https%3A%2F%2Fsemiconductor.samsung.com%2Fconsumer-storage%2Fmagician%2F) program. For Intel SSDs, download and install the [Intel Memory and Storage Tool](https://www.intel.com/content/www/us/en/download/19543/intel-memory-and-storage-tool-gui.html?v=t). SSDs from Crucial use the [Crucial Storage Executive utility](https://www.crucial.com/support/storage-executive). Microsoft Surface devices support a custom tool called the [Microsoft Surface Data Eraser](https://learn.microsoft.com/en-us/surface/surface-it-toolkit-data-eraser); check the download links in that article to determine whether you need the newer IT Toolkit or the Legacy version for older Surface devices.

Some third-party partition management tools include the option to wipe a disk completely. My favorite for this task is [MiniTool Partition Wizard](https://www.partitionwizard.com/), which includes the Wipe Disk option in free and paid versions.

**Also: [Ditch the Wi-Fi: How to add a wired network to your home without Ethernet cable](https://www.zdnet.com/home-and-office/work-life/ditch-the-wi-fi-how-to-add-a-wired-network-to-your-home-without-ethernet-cable/)**

You also can use Windows' built-in encryption tools to ensure that the entire system drive, including unused disk space, is encrypted before performing a clean install. That extra step requires some additional time, but it ensures that any data recovered from anywhere on the drive will be unreadable. And you don't need any third-party software to get the job done.

Your system drive is fully encrypted by default if you've signed in to Windows with a Microsoft account on a modern device that supports BitLocker Device Encryption (BDE). To confirm that your device supports BDE, run the System Information utility (Msinfo32.exe) as an administrator and check the Device Encryption Support entry at the bottom of the System Summary page.

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

On a system running Windows 10 Pro or Windows 11 Pro, you can use the Manage BitLocker utility (type BitLocker in the search box to find it) to encrypt the system drive and any data drives. Be sure to choose the option to encrypt the entire drive and not just the space that currently contains data.

**Also: [Where's your BitLocker recovery key? How to save a copy before the next Windows meltdown](https://www.zdnet.com/article/wheres-your-bitlocker-recovery-key-how-to-save-a-copy-before-the-next-windows-meltdown/)**

If Device Encryption isn't available, open a command prompt using the Run As Administrator option and enter this command:

**Cipher /W:C:\\**

That command "zeroes out" unused disk space, overwriting it so that it can't be recovered. This process can take a long time, so consider letting it run overnight while you concentrate on more important tasks.

_This article was originally published on May 12, 2022, and last updated on September 29, 2024\._ 

#### Featured

[Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")

[Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")

[Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")

[Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

* [Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)](https://www.zdnet.com/article/why-im-recommending-the-standard-iphone-16-over-the-pro-this-year-and-im-not-alone/ "Why I'm recommending the standard iPhone 16 over the Pro this year (and I'm not alone)")
* [Is OneDrive messing with your files? How to get your Windows storage under control](https://www.zdnet.com/article/is-onedrive-messing-with-your-files-how-to-get-your-windows-storage-under-control/ "Is OneDrive messing with your files? How to get your Windows storage under control")
* [Best early Prime Day deals under $50 to shop in October 2024](https://www.zdnet.com/article/best-early-prime-day-deals-under-50/ "Best early Prime Day deals under $50 to shop in October 2024")
* [Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other](https://www.zdnet.com/article/rust-in-linux-now-progress-pitfalls-and-why-devs-and-maintainers-need-each-other/ "Rust in Linux now: Progress, pitfalls, and why devs and maintainers need each other")

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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-fb-sounds-unlimited-grab-and-go/"><u>[New] 2024 Approved FB Sounds Unlimited Grab & Go</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-best-8-youtube-thumbnail-grabbers-you-should-know/"><u>[Updated] 2024 Approved Best 8 YouTube Thumbnail Grabbers You Should Know</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-transparent-perspective-reviewing-recordcasts-strengths/"><u>[Updated] In 2024, Transparent Perspective Reviewing RecordCast's Strengths</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-easy-video-calls-with-googles-hangouts-on-your-android/"><u>2024 Approved Easy Video Calls with Google's Hangouts on Your Android</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-samsung-galaxy-s24-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Samsung Galaxy S24 to Roku | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/comprehensive-walkthrough-acquiring-and-setting-up-epson-xp-430-drivers-on-windows-systems/"><u>Comprehensive Walkthrough: Acquiring & Setting Up Epson XP-430 Drivers on Windows Systems</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/dell-support-update-refined-communication-protocols-for-advanced-smbus-controllers/"><u>Dell Support Update: Refined Communication Protocols for Advanced SMBus Controllers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-install-latest-ch340g-serial-adapter-drivers-for-windows-10/"><u>Download & Install Latest CH340G Serial Adapter Drivers for Windows 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-the-hp-officejet-pro-6970-printer-drivers-for-windows/"><u>Download and Update the HP Officejet Pro 6970 Printer Drivers for Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/essential-software-tools-and-driver-downloads-for-optimizing-your-samsung-850-evo-performance/"><u>Essential Software Tools and Driver Downloads for Optimizing Your Samsung 850 EVO Performance</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722966652839-get-your-gigabyte-ethernet-controller-up-to-date-with-this-free-driver-package/"><u>Get Your Gigabyte Ethernet Controller Up-to-Date with This Free Driver Package</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-logitech-k400-plus-keyboard-running-comprehensive-driver-downloads/"><u>Get Your Logitech K400 Plus Keyboard Running: Comprehensive Driver Downloads</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-solve-mkv-lagging-problem-in-motorola-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How to solve MKV lagging problem in Motorola ?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-the-fix-of-csr8510-a10-driver-errors-in-windows-proven-techniques-and-advice/"><u>Mastering the Fix of CSR8510 A10 Driver Errors in Windows: Proven Techniques and Advice</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/premier-essentials-seamless-audio-switching/"><u>Premier Essentials Seamless Audio Switching</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-your-disabled-apple-iphone-7-without-itunes-in-5-ways-by-drfone-ios/"><u>Unlock Your Disabled Apple iPhone 7 Without iTunes in 5 Ways</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-in-2024-linux-on-a-chromebook-the-ultimate-setup-tutorial/"><u>Updated In 2024, Linux on a Chromebook The Ultimate Setup Tutorial</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

