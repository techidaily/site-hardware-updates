---
title: "Restoring Default Sound Configuration on Windows: A Step-by-Step Guide"
date: 2025-01-19T18:37:39.517Z
updated: 2025-01-24T17:18:06.058Z
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
<li><a href="https://youtube-data.techidaily.com/aptivate-masses-social-media-strategies-for-youtube-for-2024/"><u>[New] Captivate Masses Social Media Strategies for YouTube for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-the-blueprint-for-lifelong-memories-storing-vintage-photos-digitally-for-2024/"><u>[New] The Blueprint for Lifelong Memories Storing Vintage Photos Digitally for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/amd-rx-580-video-card-driver-upgrade-quick-downloads-for-smooth-gaming-performance/"><u>AMD RX 580 Video Card Driver Upgrade: Quick Downloads for Smooth Gaming Performance</u></a></li>
<li><a href="https://tech-haven.techidaily.com/crafting-imaginative-tales-using-chatgpt-strategies-for-success/"><u>Crafting Imaginative Tales Using ChatGPT: Strategies for Success</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-amd-radeon-rx-580-graphics-driver-simple-steps/"><u>Download & Update AMD Radeon RX 580 Graphics Driver - Simple Steps</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-upgrade-your-intel-raid-drivers-on-windows-compatible-with-windows-111087/"><u>Download & Upgrade Your Intel RAID Drivers on Windows - Compatible with Windows 11/10/8/7</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-bcm20702a0-drivers-for-windows-fast-and-simple-installation/"><u>Download BCM20702A0 Drivers for Windows - Fast and Simple Installation</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/downloading-and-installing-the-right-audio-drivers-for-your-logitech-speakers-on-windows-10-7-or-8/"><u>Downloading and Installing the Right Audio Drivers for Your Logitech Speakers on Windows 10, 7 or 8</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-windows-11-ease-of-use-with-improved-run-feature/"><u>Enhancing Windows 11 Ease of Use with Improved Run Feature</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/find-and-update-your-toshiba-laptops-drivers-on-a-windows-operating-system/"><u>Find and Update Your Toshiba Laptop's Drivers on a Windows Operating System</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-geforce-rtx-ebyte-3080-drivers-for-your-pc-supports-windows-1087-systems/"><u>Get the Newest GeForce RTX Ebyte 3080 Drivers for Your PC - Supports Windows 10/8/7 Systems</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-fixes-how-to-recover-forgotten-icloud-password-on-your-apple-iphone-12-mini-by-drfone-ios/"><u>In 2024, Easy Fixes How To Recover Forgotten iCloud Password On your Apple iPhone 12 mini</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-top-10-text-boosting-techniques-in-videos/"><u>In 2024, Top 10 Text Boosting Techniques in Videos</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-pokemon-evolve-with-a-dawn-stone-for-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What Pokémon Evolve with A Dawn Stone For Lava Blaze Curve 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/keeping-facts-alive-facebook-amps-up-against-hoaxes/"><u>Keeping Facts Alive: Facebook Amps Up Against Hoaxes</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ryzen-9-9950x-outperforms-core-i9-14900k-by-18-with-efficient-250w-cpu-power/"><u>Ryzen 9 9950X Outperforms Core I9-14900K by 18% with Efficient 250W CPU Power</u></a></li>
<li><a href="https://fox-links.techidaily.com/sustainable-design-in-action-the-huawei-p10s-environmental-approach-for-2024/"><u>Sustainable Design in Action The Huawei P10’s Environmental Approach for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/tomahawk-msi-b350-motherboard-drivers-free-download-guide-for-windows-10-and-7-users/"><u>Tomahawk MSI B350 Motherboard Drivers: Free Download Guide for Windows 10 and 7 Users</u></a></li>
<li><a href="https://some-approaches.techidaily.com/wie-man-vhs-filme-in-hochwertige-dvds-konvertiert-und-sie-anschliessend-auf-das-computersystem-uberspielt/"><u>Wie Man VHS Filme in Hochwertige DVDs Konvertiert Und Sie Anschließend Auf Das Computersystem Überspielt</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

