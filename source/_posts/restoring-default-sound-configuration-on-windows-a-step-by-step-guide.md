---
title: "Restoring Default Sound Configuration on Windows: A Step-by-Step Guide"
date: 2025-01-14T18:07:04.245Z
updated: 2025-01-18T17:01:03.453Z
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
<li><a href="https://twitter-videos.techidaily.com/new-ignite-engagement-on-twitch-alive-tweeting-techniques/"><u>[New] Ignite Engagement on Twitch Alive Tweeting Techniques</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-unveiling-the-secrets-of-kinemaster-usage-and-ranking-alternatives-1-10/"><u>[Updated] 2024 Approved Unveiling the Secrets of KineMaster Usage & Ranking Alternatives 1-10</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-visual-wit-a-guide-to-making-memes-shine/"><u>2024 Approved Visual Wit A Guide to Making Memes Shine</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722974584286-bluetooth-compatibility-upgrade-premium-msi-driver-software-tailored-for-windows-11-and-10-free-download/"><u>Bluetooth Compatibility Upgrade: Premium MSI Driver Software Tailored for Windows 11 & 10 - Free Download</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/como-actualizar-manualmente-los-drivers-en-windows-cuando-no-hay-conexion-a-internet-disponible/"><u>Cómo Actualizar Manualmente Los Drivers en Windows Cuando No Hay Conexión a Internet Disponible</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-tutorial-setting-up-iphone-device-on-windows-11/"><u>Complete Tutorial: Setting Up iPhone Device on Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-compatible-software-for-your-logitech-k400-plus-peripherals/"><u>Download & Update: Compatible Software for Your Logitech K400 Plus Peripherals</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-installation-sm-bus-controller-program-downloads-for-windows-users-versions-11-10-8-and-s/"><u>Easy Installation: SM Bus Controller Program Downloads for Windows Users (Versions 11, 10, 8 & S)</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-samsung-galaxy-xcover-6-pro-tactical-edition-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Samsung Galaxy XCover 6 Pro Tactical Edition 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-fix-and-download-mouse-drivers-for-windows-7-troubleshooting-steps/"><u>How to Fix and Download Mouse Drivers for Windows 7 - Troubleshooting Steps</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-google-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Google FRP</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-how-to-put-a-background-on-a-green-screen/"><u>New 2024 Approved How to Put a Background on A Green Screen</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/perfecting-visual-output-incorporating-luts-into-your-ae-projects-for-2024/"><u>Perfecting Visual Output Incorporating LUTs Into Your AE Projects for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/revamp-your-pcs-power-management-how-to-update-battery-drivers-in-windows-with-ease/"><u>Revamp Your PC’s Power Management: How to Update Battery Drivers in Windows with Ease</u></a></li>
<li><a href="https://solve-hot.techidaily.com/roholan-paling-efisien-metode-mengubah-untuk-memperluas-capacity-ssd-pada-windows-1011-versi-tertinggi/"><u>Roholan Paling Efisien: Metode Mengubah Untuk Memperluas Capacity SSD Pada Windows 10/11 Versi Tertinggi</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/speedy-intel-nuc-revision-user-friendly-steps-for-immediate-driver-update/"><u>Speedy Intel NUC Revision | User-Friendly Steps for Immediate Driver Update</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-updating-your-amd-rx-580-driver-with-ease-and-speed/"><u>Step-by-Step Guide: Updating Your AMD RX 580 Driver with Ease & Speed</u></a></li>
<li><a href="https://article-files.techidaily.com/the-secrets-to-effortless-iphone-photo-sorting-and-synchronizing-with-icloud/"><u>The Secrets to Effortless iPhone Photo Sorting & Synchronizing with iCloud</u></a></li>
<li><a href="https://extra-information.techidaily.com/win11s-quickest-image-viewing-experience/"><u>Win11's Quickest Image Viewing Experience</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

