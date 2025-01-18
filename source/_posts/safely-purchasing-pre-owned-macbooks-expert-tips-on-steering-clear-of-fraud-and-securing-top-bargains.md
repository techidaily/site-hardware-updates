---
title: "Safely Purchasing Pre-Owned MacBooks: Expert Tips on Steering Clear of Fraud & Securing Top Bargains"
date: 2025-01-14T17:05:49.805Z
updated: 2025-01-18T18:12:48.794Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e20731976346abc5e9e51e32ccd4741e92a00f139a0758d467d321b1a71642cd.jpg
---

## Remove All Traces of Sensitive Info on Your Laptop Safely & Free: Expert Tips

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
<li><a href="https://fox-glue.techidaily.com/new-premium-web-choices-for-shiny-3d-type-designs-for-2024/"><u>[New] Premium Web Choices for Shiny, 3D Type Designs for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/update-intel-iris-plus-graphics-640-driver-quickly-and-easily/"><u>[UPDATE] Intel Iris Plus Graphics 640 Driver | Quickly & Easily</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-favorites-compiled-top-6-fb-lite-downloads/"><u>[Updated] In 2024, Favorites Compiled #Top 6 FB Lite Downloads</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-installation-for-insignia-usb-network-adapter-drivers/"><u>Download & Installation for Insignia USB Network Adapter Drivers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/dvdq/"><u>DVDからパソコンに移動する上達テクニッQ: ジャニーズ系アーティストのライブを保存する方法</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/epson-v500-scanner-software-download-latest-version/"><u>Epson V500 Scanner Software Download - Latest Version</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-find-and-install-the-correct-hp-laserjet-1018-printer-drivers/"><u>How to Find and Install the Correct HP LaserJet 1018 Printer Drivers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-latest-drivers-for-your-lenovo-x1-carbon-on-windows-117-with-ease/"><u>How to Get the Latest Drivers for Your Lenovo X1 Carbon on Windows 11/7 with Ease</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-laserjet-p1102w-driver-download-for-windows/"><u>HP LaserJet P1102w Driver Download for Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/improve-your-samsung-phones-performance-by-updating-the-usb-driver-what-you-need-to-know/"><u>Improve Your Samsung Phone's Performance by Updating the USB Driver - What You Need To Know</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-transforming-snaps-into-animated-characters-in-snapchat/"><u>In 2024, Transforming Snaps Into Animated Characters in Snapchat</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-your-firestick-simple-steps-to-sync-the-remote-control/"><u>Mastering Your Firestick: Simple Steps to Sync the Remote Control</u></a></li>
<li><a href="https://fake-location.techidaily.com/prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-fixes-overcoming-logitech-f710-driver-issues-across-multiple-windows-operating-systems/"><u>Quick Fixes: Overcoming Logitech F710 Driver Issues Across Multiple Windows Operating Systems</u></a></li>
<li><a href="https://win11.techidaily.com/reinstating-functional-windows-rulesets-in-outlook/"><u>Reinstating Functional Windows Rulesets in Outlook</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/makers-playbook-recipes-for-attractive-channel-names-for-2024/"><u>Tastemakers' Playbook Recipes for Attractive Channel Names for 2024</u></a></li>
<li><a href="https://program-issues.techidaily.com/tips-and-tricks-for-a-smooth-experience-with-tales-of-arise-no-more-crashes/"><u>Tips & Tricks for a Smooth Experience with Tales of Arise – No More Crashes!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6xGqSETroqA?si=4C1GPgXi-AksR_oO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

