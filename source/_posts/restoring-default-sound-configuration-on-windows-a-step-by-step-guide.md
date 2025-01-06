---
title: "Restoring Default Sound Configuration on Windows: A Step-by-Step Guide"
date: 2025-01-02T06:34:59.374Z
updated: 2025-01-06T12:26:07.016Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f60c71115611cc9fe9bdefefd0669c874b252cd453080c3b9c40526ec436a000.jpg
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
<li><a href="https://article-helps.techidaily.com/new-2024-approved-navigating-video-multitasking-in-chromes-pip-mode-on-all-devices/"><u>[New] 2024 Approved Navigating Video Multitasking in Chrome’s PIP Mode on All Devices</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-visionaries-crafting-next-gen-vr-worlds-for-2024/"><u>[New] Visionaries Crafting Next-Gen VR Worlds for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-feast-your-eyes-enjoyment-without-cost-watch-9-christmas-films-online/"><u>[Updated] Feast Your Eyes, Enjoyment Without Cost Watch 9 Christmas Films Online</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-unveiling-the-most-reliable-9-mic-devices-for-recording/"><u>[Updated] Unveiling the Most Reliable 9 Mic Devices for Recording</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-as-a-tool-for-effective-work-scheduling/"><u>ChatGPT as a Tool for Effective Work Scheduling</u></a></li>
<li><a href="https://some-tips.techidaily.com/discover-the-enhancements-in-apples-first-visionos-update-profile-revamps-and-beyond-insights/"><u>Discover the Enhancements in Apple's First VisionOS Update: Profile Revamps & Beyond | Insights</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-installation-guide-the-newest-sapphire-graphics-drivers-for-windows-users/"><u>Download and Installation Guide: The Newest Sapphire Graphics Drivers for Windows Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/effortless-guide-to-refresh-lenovo-system-firmware-and-power-control-modules/"><u>Effortless Guide to Refresh Lenovo System Firmware & Power Control Modules</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/guide-to-troubleshooting-and-updating-corsair-h115i-drivers-on-windows-platforms/"><u>Guide to Troubleshooting and Updating Corsair H115i Drivers on Windows Platforms</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-color-laserjet-pro-m45n-driver-download-guide-compatible-software/"><u>HP Color LaserJet Pro M45n Driver Download Guide - Compatible Software</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-no-gps-signal-heres-every-possible-solution-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go No GPS Signal? Heres Every Possible Solution On Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/score-the-latest-upgrade-to-the-magicard-rio-pro-driving-experience-on-windows-os/"><u>Score the Latest Upgrade to the Magicard Rio Pro Driving Experience on Windows OS</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/tech-giant-explains-repeated-crashes-on-latest-laptop-processors-distinguishing-them-from-known-desktop-chip-vulnerability/"><u>Tech Giant Explains Repeated Crashes on Latest Laptop Processors, Distinguishing Them From Known Desktop Chip Vulnerability</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/the-next-generation-previewing-intels-arrow-lake-s-series-for-a-potential-holiday-release-in-december/"><u>The Next Generation: Previewing Intel's Arrow Lake-S Series for a Potential Holiday Release in December</u></a></li>
<li><a href="https://techtrends.techidaily.com/ultimate-guide-downloading-applications-onto-your-samsung-smart-tv/"><u>Ultimate Guide: Downloading Applications Onto Your Samsung Smart TV</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Vivo Y28 5G? | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zmXpl6irBYk?si=BXjGpQr6PXFcqhCI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

