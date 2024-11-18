---
title: "Step-by-Step Guide: Installing More Memory in Your Notebook - Tips From ZDNet"
date: 2024-11-15T18:54:14.754Z
updated: 2024-11-17T19:24:50.492Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/134f01974d541e3e4f7e678a539e306f85d908190cede197af26c62a5bdec50a.png
---

## How to Securely Wipe Data From Your Windows Laptop: A Step-by-Step Guide for Free

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

[The 10 best laptop deals ahead of October Prime Day](https://www.zdnet.com/article/best-early-prime-day-laptop-deals-2024/ "The 10 best laptop deals ahead of October Prime Day")

[Google's AI podcast tool transforms your text into stunningly lifelike audio - for free](https://www.zdnet.com/article/googles-ai-podcast-tool-transforms-your-text-into-stunningly-lifelike-audio-for-free/ "Google's AI podcast tool transforms your text into stunningly lifelike audio - for free")

[My favorite Garmin sports watch ever just got a new version, and it costs $200 less](https://www.zdnet.com/article/my-favorite-garmin-sports-watch-ever-just-got-a-new-version-and-it-costs-200-less/ "My favorite Garmin sports watch ever just got a new version, and it costs $200 less")

[5 nearly hidden Android features you should already be using](https://www.zdnet.com/article/5-nearly-hidden-android-features-you-should-already-be-using/ "5 nearly hidden Android features you should already be using")

* [The 10 best laptop deals ahead of October Prime Day](https://www.zdnet.com/article/best-early-prime-day-laptop-deals-2024/ "The 10 best laptop deals ahead of October Prime Day")
* [Google's AI podcast tool transforms your text into stunningly lifelike audio - for free](https://www.zdnet.com/article/googles-ai-podcast-tool-transforms-your-text-into-stunningly-lifelike-audio-for-free/ "Google's AI podcast tool transforms your text into stunningly lifelike audio - for free")
* [My favorite Garmin sports watch ever just got a new version, and it costs $200 less](https://www.zdnet.com/article/my-favorite-garmin-sports-watch-ever-just-got-a-new-version-and-it-costs-200-less/ "My favorite Garmin sports watch ever just got a new version, and it costs $200 less")
* [5 nearly hidden Android features you should already be using](https://www.zdnet.com/article/5-nearly-hidden-android-features-you-should-already-be-using/ "5 nearly hidden Android features you should already be using")

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
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-advanced-techniques-in-itunes-video-saving/"><u>[Updated] 2024 Approved Advanced Techniques in iTunes Video Saving</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-secure-apps-for-hidden-instagram-stories/"><u>[Updated] 2024 Approved Secure Apps for Hidden Instagram Stories</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-tools-and-techniques-adding-frames-to-digital-images-2023-edition/"><u>[Updated] Best Tools & Techniques - Adding Frames to Digital Images, 2023 Edition</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-best-front-row-non-sports-options/"><u>2024 Approved Best Front Row Non-Sports Options</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/discovering-cutting-edge-hardware-with-toms-technology-hub/"><u>Discovering Cutting-Edge Hardware with Tom's Technology Hub</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722968452582-download-and-install-m-audio-fast-track-drivers-for-various-windows-versions-today/"><u>Download & Install M-Audio Fast Track Drivers for Various Windows Versions Today</u></a></li>
<li><a href="https://win-answers.techidaily.com/far-cry-6-no-more-blank-screens-ultimate-fix-guide/"><u>Far Cry 6 No More Blank Screens: Ultimate Fix Guide</u></a></li>
<li><a href="https://fox-http.techidaily.com/flight-path-perfection-essential-insights-for-drone-racers-and-top-5-models-for-2024/"><u>Flight Path Perfection Essential Insights for Drone Racers & Top 5 Models for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-infinix-hot-30i-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Infinix Hot 30i | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/lift-mood-and-performance-20-fitness-playlists-ranked-right-for-2024/"><u>Lift Mood & Performance 20 Fitness Playlists Ranked Right for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/nvidia-drivers-downloads-step-by-step-installation-guide/"><u>NVIDIA Drivers Downloads: Step-by-Step Installation Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/seamless-downloading-of-bluetooth-drivers-for-windows-7-users/"><u>Seamless Downloading of Bluetooth Drivers for Windows 7 Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-tutorial-instantly-update-or-download-canon-drivers-on-windows/"><u>Step-by-Step Tutorial: Instantly Update or Download Canon Drivers on Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/the-filmmakers-guide-to-avoiding-overused-channel-labels-for-2024/"><u>The Filmmaker's Guide to Avoiding Overused Channel Labels for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1723262426304-unleash-your-strength-on-silicon-and-circuits-at-the-2024-international-servers-out-challenge/"><u>Unleash Your Strength on Silicon and Circuits at the 2024 International Servers-Out Challenge</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unveiling-the-latest-in-tech-a-journey-with-toms-hardware-reviews/"><u>Unveiling the Latest in Tech: A Journey with Tom's Hardware Reviews</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

