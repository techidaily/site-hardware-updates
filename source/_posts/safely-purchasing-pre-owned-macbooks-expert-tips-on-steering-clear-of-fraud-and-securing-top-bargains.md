---
title: "Safely Purchasing Pre-Owned MacBooks: Expert Tips on Steering Clear of Fraud & Securing Top Bargains"
date: 2025-01-29T06:49:14.808Z
updated: 2025-02-02T16:51:26.791Z
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
<li><a href="https://youtube-lab.techidaily.com/obile-and-desktop-techniques-for-youtube-short-video-submission-for-2024/"><u>[New] Mobile & Desktop Techniques for YouTube Short Video Submission for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-flying-vs-capturing-dji-action-gopro-max-instax360/"><u>2024 Approved Flying Vs. Capturing DJi Action, GoPro Max, InstaX360</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/affordable-quality-dell-inspiron-with-16-inch-display-outperforms-expectations-smart-purchase-guide/"><u>Affordable Quality: Dell Inspiron with 16-Inch Display Outperforms Expectations - Smart Purchase Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/essential-gadgets-every-wanderer-needs-in-2vearlier-years-with-insider-tips-by-the-tech-experts-at-zdnet/"><u>Essential Gadgets Every Wanderer Needs in 2Vearlier Years, with Insider Tips by the Tech Experts at ZDNET</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/exclusive-pre-prime-day-bargains-at-best-buy-insider-tips-from-zdnet/"><u>Exclusive Pre-Prime Day Bargains at Best Buy - Insider Tips From ZDNet</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/gopros-battle-royale-hero5-b-stacked-against-session/"><u>GoPro's Battle Royale Hero5 B Stacked Against Session</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-stop-frequent-content-warning-browser-issues-on-windows-based-desktops/"><u>How To Stop Frequent 'Content Warning' Browser Issues on Windows-Based Desktops</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-oppo-reno-11-5g-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Oppo Reno 11 5G</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-2024-approved-how-to-make-video-slideshow-with-your-travel-photos/"><u>New 2024 Approved How to Make Video Slideshow with Your Travel Photos</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-wacom-tablet-errors-effective-fixes-and-troubleshooting-steps/"><u>Resolving Wacom Tablet Errors: Effective Fixes & Troubleshooting Steps</u></a></li>
<li><a href="https://data-recovery.techidaily.com/stellardata-salvage-hub/"><u>StellarData Salvage Hub</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-24-delightful-dell-deals-on-the-festive-season-compare-prices-from-best-buy-amazon-and-newegg-featured-by-zdnet/"><u>Top 24 Delightful Dell Deals on the Festive Season: Compare Prices From Best Buy, Amazon & Newegg - Featured by ZDNet</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-7-premium-adjustable-standing-desks-of-2023-insights/"><u>Top 7 Premium Adjustable Standing Desks of 2023 - Insights</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-deal-alert-drop-350-off-your-alienamoe-aurora-r13-purchase-gamers-insider-tips/"><u>Top Deal Alert: Drop $350 Off Your Alienamoe Aurora R13 Purchase, Gamers! Insider Tips</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unbeatable-deal-alert-amazon-drops-prices-on-the-8tb-samsung-t5-ssd-to-just-36-off-after-prime-day-exclusive-coverage-from-zdnet/"><u>Unbeatable Deal Alert! Amazon Drops Prices on the 8TB Samsung T5 SSD to Just 36% Off After Prime Day - Exclusive Coverage From ZDNet</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unlock-an-unmatched-gaming-experience-top-ranking-speakers-go-on-discount-at-best-buy-exclusive-review/"><u>Unlock an Unmatched Gaming Experience: Top-Ranking Speakers Go On Discount at Best Buy - Exclusive Review</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-mac-video-editor-reviews-find-the-perfect-tool-for-your-needs/"><u>Updated In 2024, Mac Video Editor Reviews Find the Perfect Tool for Your Needs</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

