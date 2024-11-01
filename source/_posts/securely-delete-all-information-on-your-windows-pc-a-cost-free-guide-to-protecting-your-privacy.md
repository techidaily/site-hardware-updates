---
title: "Securely Delete All Information on Your Windows PC: A Cost-Free Guide to Protecting Your Privacy"
date: 2024-10-29T18:01:42.801Z
updated: 2024-11-01T20:57:09.511Z
tags:
  - laptops
categories:
  - tech
thumbnail: https://thmb.techidaily.com/b65bf539ad3bc7b67798ef76b0171c5880f30454ab3ea8bd7a6f0e0d486378c6.jpg
---

## How to Securely Wipe Your Windows PC: A Step-by-Step Guide to Protecting Your Privacy at No Cost – Insights

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-implementing-visual-learning-strategies-in-classrooms/"><u>[New] 2024 Approved Implementing Visual Learning Strategies in Classrooms</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-unraveling-zdsofts-screen-monitor-magic/"><u>[New] 2024 Approved Unraveling ZDSoft's Screen Monitor Magic</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/-step-by-step-guide-for-earning-with-youtube-shorts/"><u>[New] A Step-by-Step Guide for Earning with YouTube Shorts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-advanced-tips-excelling-at-slide-show-recordings-for-2024/"><u>[New] Advanced Tips Excelling at Slide Show Recordings for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/android-and-iphone-collage-kings-the-best-montage-apps/"><u>Android & iPhone Collage Kings The Best Montage Apps</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-tutorial-download-and-install-canon-mf4500-printer-driver-today/"><u>Complete Tutorial: Download & Install Canon MF4500 Printer Driver Today!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-latest-updates-for-canon-eos-dslr-camera-model-d530/"><u>Download and Latest Updates for Canon EOS DSLR Camera Model D530</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/effortless-vga-signal-transfer-download-startechs-hdmivga-dual-head-adapter/"><u>Effortless VGA Signal Transfer: Download StarTech's HDMI/VGA Dual Head Adapter</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-download-ultimate-guide-to-installing-msi-sound-card-drivers-on-your-pc/"><u>Free Download: Ultimate Guide to Installing MSI Sound Card Drivers on Your PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-acer-device-online-free-wifi-drivers-and-step-by-step-setup-tutorials/"><u>Get Your Acer Device Online: FREE WiFi Drivers & Step-by-Step Setup Tutorials</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/guide-finding-and-downloading-epson-xp-830-driver-a-step-by-step-approach/"><u>Guide: Finding & Downloading Epson XP-830 Driver - A Step by Step Approach</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-motorola-moto-g24-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Motorola Moto G24 Phone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-ultimate-selection-top-hdr-camera-picks/"><u>In 2024, Ultimate Selection Top HDR Camera Picks</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/msi-b350-toms-hardware-ultimate-driver-downloads-and-support-compatible-with-windows-11-and-7/"><u>MSI B350 TOM'S HARDWARE: Ultimate Driver Downloads & Support Compatible with Windows 11 and 7</u></a></li>
<li><a href="https://os-tips.techidaily.com/reviving-your-memories-step-by-step-guide-to-retrieving-iphoneipad-images-from-an-itunes-backup/"><u>Reviving Your Memories: Step-by-Step Guide to Retrieving iPhone/iPad Images From an iTunes Backup</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/toms-tech-advice-expert-gadget-guidance/"><u>Tom's Tech Advice: Expert Gadget Guidance</u></a></li>
<li><a href="https://solve-manuals.techidaily.com/1728504048876-windows-pc/"><u>Windows PC でパスワードを利用したバックアップの暗号化手順</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880931/19272" target="_top" id="1880931">
  <img src="//a.impactradius-go.com/display-ad/19272-1880931" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880931/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

