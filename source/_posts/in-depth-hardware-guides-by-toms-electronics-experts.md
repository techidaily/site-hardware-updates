---
title: In-Depth Hardware Guides by Tom's Electronics Experts
date: 2024-08-13T11:21:51.345Z
updated: 2024-08-14T11:21:51.345Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/R7fx59jkBCG4MFPsgpq4dG-320-80.jpg
---

## Unveiling Cutting-Edge Gadgets with Tom's Hardware Review

Intel has[announced that it has found the root](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) [cause](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) of the crashing issues plaguing its CPUs. The company will issue a microcode update to address the issues by mid-August, ostensibly ending the long-running saga that began when the first sporadic reports of CPU crashing errors surfaced in December 2022 and grew to a crescendo by the end of 2023\. Intel's response comes after complaints about the issue, which causes PCs to inexplicably crash/BSOD during gaming and other workloads,[reached a fever pitch](https://www.tomshardware.com/pc-components/cpus/game-publisher-claims-100-crash-rate-with-intel-cpus-alderon-games-says-company-sells-defective-13th-and-14th-gen-chips) in recent weeks. However, the microcode update will not repair impacted processors. Intel also confirmed a rumored issue with via oxidation in its 7nm node, but said those issues were corrected in 2023 and didn't contribute to the failures.

 Intel's advisory says an erroneous CPU microcode is the root cause of the incessant instability issues. The microcode caused the CPU to request elevated voltage levels, resulting in the processor operating outside its safe boundaries. Intel is now validating a microcode patch to correct the issues, with its release slated for mid-August. This patch will be distributed through BIOS updates from motherboard OEMs and via Windows updates, so the timing for end-user availability could vary.

 The bug causes irreversible degradation of the impacted processors. We're told that the microcode patch will_not_ repair processors already experiencing crashes, but it is expected to prevent issues on processors that aren't currently impacted by the issue. For now, it is unclear if CPUs exposed to excessive voltage have suffered from invisible degradation or damage that hasn't resulted in crashes yet but could lead to errors or crashes in the future.

 Intel advises all customers having issues to seek help from its customer support. Because the microcode update will not repair impacted processors, the company will continue to replace them. Intel has pledged to grant RMAs to all impacted customers.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 The company had previously advised its customers to stick with the basic power guidelines for its processors, rather than running them at fully unlocked settings, as it worked through the issues. Those instructions, [which you can see here](https://www.tomshardware.com/pc-components/cpus/intel-issues-official-statement-on-core-k-series-crashes-stick-to-intels-official-power-profiles) , remain in effect for now, and Intel hasn't issued any new workarounds for impacted customers. It is unclear if Intel will lift the existing restrictions after it issues the patch.

 Intel had previously[fixed an eTVB bug](https://www.tomshardware.com/pc-components/cpus/intel-denies-reports-that-it-identified-a-root-cause-for-core-i9-crashing-issues-investigation-continues) that contributed to the problems, but now says microcode is the root cause. We're told that the microcode patch currently doesn't exhibit any adverse performance impact (i.e., the chip running slower), but testing is ongoing. We can expect Intel to share more information about performance in the future.

 Intel isn't sharing many deep-dive details about the bug yet but says it will continue its validation process to ensure the microcode fully addresses the issues. The company will release more details about the bug itself in the future.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## Intel statement on via oxidation

**Short answer:** We can confirm there was a via Oxidation manufacturing issue (addressed back in 2023) but it is not related to the instability issue.

**Long answer:**   _We can confirm that the via Oxidation manufacturing issue affected some early Intel Core 13th Gen desktop processors. However, the issue was root caused and addressed with manufacturing improvements and screens in 2023\. We have also looked at it from the instability reports on Intel Core 13th Gen desktop processors and the analysis to-date has determined that only a small number of instability reports can be connected to the manufacturing issue._

 _For the Instability issue, we are delivering a microcode patch which addresses exposure to elevated voltages which is a key element of the Instability issue. We are currently validating the microcode patch to ensure the instability issues for 13th/14th Gen are addressed. -_ Intel representative[via Reddit](https://www.reddit.com/r/intel/comments/1e9mf04/comment/lefz09c/) .


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
<li><a href="https://some-knowledge.techidaily.com/new-how-to-turn-on-and-use-automatic-hdr-high-dynamic-range-in-windows-11/"><u>[New] How to Turn On and Use Automatic HDR (High Dynamic Range) in Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-amazon-prime-hits-twitters-trendiest-watchers-and-lovers/"><u>[New] In 2024, Amazon Prime Hits  Twitter's Trendiest Watchers & Lovers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-popularize-with-pizzazz-infuse-instagram-reels-with-tiktok-energy/"><u>[New] In 2024, Popularize with Pizzazz  Infuse Instagram Reels With TikTok Energy</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-proven-practice-for-preserving-playthroughs-tips-and-tricks-for-recording-roblox-gameplay-on-a-mac/"><u>[New] In 2024, Proven Practice for Preserving Playthroughs  Tips & Tricks for Recording Roblox Gameplay on a Mac</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-navigating-illness-with-immersive-systems/"><u>[New] Navigating Illness with Immersive Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-ultimate-5-book-tt-showcases-for-readers/"><u>[New] The Ultimate 5 Book TT Showcases for Readers</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-tiktok-and-twittersphere-crossover-the-viral-vids/"><u>[Updated] In 2024, TikTok and Twittersphere Crossover  The Viral Vids</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-innovating-realms-history-of-vr-for-2024/"><u>[Updated] Innovating Realms  History of VR for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/2024-approved-essential-guide-to-recording-films-on-windowsmac-and-phones/"><u>2024 Approved  Essential Guide to Recording Films on Windows/Mac & Phones</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-mr-beasts-financial-portrait/"><u>2024 Approved  Mr. Beast’s Financial Portrait</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/comprehensive-guide-installing-intel-iris-xe-lp-graphics-655-drivers-on-pcs-with-windows-10-or-11/"><u>Comprehensive Guide: Installing Intel Iris Xe LP Graphics 655 Drivers on PCs with Windows 10 or 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-newest-drivers-for-rtx-2080-on-windows-10-7-and-8-get-them-now/"><u>Download the Newest Drivers for RTX 2080 on Windows 10, 7 & 8 - Get Them Now</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-guide-to-downloading-and-installing-hp-deskjet-inkjet-printer-drivers-for-windows-10-devices/"><u>Easy Guide to Downloading and Installing HP Deskjet Inkjet Printer Drivers for Windows 10 Devices</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-steps-to-downloading-the-right-samsung-adb-driver/"><u>Easy Steps to Downloading the Right Samsung ADB Driver</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/fix-lenovo-usb-driver-issues-easily/"><u>Fix Lenovo USB Driver Issues Easily</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-brother-mfc-9130cw-printer-software-installation-file/"><u>Free Brother MFC-9130CW Printer Software Installation File</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-geforce-rtx-3080-drivers-downloaded-compatible-with-windows-10-8-and-7/"><u>Free GeForce RTX 3080 Drivers Downloaded - Compatible with Windows 10, 8 & 7</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-surface-pro-ebx4-drivers-installed-in-windows-step-by-step/"><u>Get the Latest Surface Pro Ebx4 Drivers Installed in Windows: Step-by-Step</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-amd-radeon-vega-64-up-to-date-download-and-install-drivers-easily-on-windows-pcs/"><u>Get Your AMD Radeon VEGA 64 Up to Date - Download & Install Drivers Easily on Windows PCs</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-corsair-keyboard-up-and-running-on-windows-with-these-safe-driver-downloads/"><u>Get Your Corsair Keyboard Up & Running on Windows with These Safe Driver Downloads</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722967906015-get-your-rtx-2080-gpu-updated-drivers-for-win10-and-win11-available-now/"><u>Get Your RTX 2080 GPU Updated: Drivers for Win10 and Win11 Available Now!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-efficiently-find-and-update-the-hp-laserjet-pro-m402n-printer-driver-for-windows-computers/"><u>How to Efficiently Find and Update the HP LaserJet Pro M402n Printer Driver for Windows Computers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hp-officejet-inkjet-n-pro-4650-download-the-latest-drivers-specifically-tailored-for-microsoft-windows-systems/"><u>HP Officejet Inkjet N Pro 4650: Download the Latest Drivers Specifically Tailored for Microsoft Windows Systems</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Apple iPhone 15 Plus? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-the-best-compatible-drivers-for-your-epson-et-2750-printer-on-windows-108x-free-download-options/"><u>Install the Best Compatible Drivers for Your Epson ET-2750 Printer on Windows 10/8.x: Free Download Options</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/keeping-your-displays-clean-update-and-install-nvidiaamd-gpu-drivers-for-windows/"><u>Keeping Your Displays Clean: Update and Install Nvidia/AMD GPU Drivers for Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-canon-mp280-software-downloads-for-windows-11-8-7-users/"><u>Latest Canon MP280 Software Downloads for Windows 11 / 8 / 7 Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/mastering-arduino-nano-driver-installation-a-simple-guide-for-windows-users/"><u>Mastering Arduino Nano Driver Installation: A Simple Guide for Windows Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/most-recent-driver-updates-for-nvidia-geforce-rtx-3080-ti-win-11-8-and-7-support/"><u>Most Recent Driver Updates for NVIDIA GeForce RTX 3080 Ti: Win 11, 8 & 7 Support</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-the-top-6-alternatives-to-twitch-for-your-streaming-needs-for-2024/"><u>New The Top 6 Alternatives to Twitch for Your Streaming Needs for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/nvidia-quadro-windows-10-driver-download-enhance-your-gpu-performance-with-dch/"><u>NVIDIA Quadro Windows 10 Driver Download - Enhance Your GPU Performance with DCH</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/optimize-your-gameplay-enhancing-performance-with-an-updated-asus-radeon-rx-970-graphics-card/"><u>Optimize Your Gameplay: Enhancing Performance with an Updated ASUS Radeon RX 970 Graphics Card</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-and-simple-steps-to-downloading-the-latest-scansnap-driver-for-windows-pcs/"><u>Quick and Simple Steps to Downloading the Latest ScanSnap Driver for Windows PCs</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-download-for-intels-wireless-ac-7260-card-get-the-latest-driver-here/"><u>Quick Download for Intel's Wireless AC 7260 Card - Get the Latest Driver Here!</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/quick-guide-capturing-moments-with-snap-in-real-time-conferencing/"><u>Quick Guide  Capturing Moments with Snap in Real-Time Conferencing</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-guide-updating-your-dell-inspiron-70017432g7-laptops-drivers-with-simple-steps/"><u>Quick Guide: Updating Your Dell Inspiron 7001/7432G7 Laptop's Drivers with Simple Steps</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quickly-obtain-your-brother-hl-3170cdw-printer-drives/"><u>Quickly Obtain Your Brother HL-3170cdw Printer Drives</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/script-strategies-for-captivating-youtube-audiences-for-2024/"><u>Script Strategies for Captivating YouTube Audiences for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/seamless-setup-how-to-update-your-crucial-ssd-software/"><u>Seamless Setup: How To Update Your Crucial SSD Software</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/secure-and-simple-downloads-for-amd-ryzen-graphics-drivers/"><u>Secure and Simple Downloads for AMD Ryzen Graphics Drivers</u></a></li>
<li><a href="https://extra-tips.techidaily.com/simple-strategies-for-smooth-underwater-moviemaking/"><u>Simple Strategies for Smooth Underwater Moviemaking</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722977311069-streamlined-access-to-the-zebra-gk420d-interface-start-downloading-today/"><u>Streamlined Access to the Zebra GK420D Interface - Start Downloading Today!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-full-guide-to-instagrams-per-video-limit/"><u>The Full Guide to Instagram's Per-Video Limit</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/update-your-lenovo-ideapad-100-to-the-latest-drivers-compatible-with-windows-11/"><u>Update Your Lenovo IdeaPad 100 to the Latest Drivers Compatible with Windows 11</u></a></li>
</ul></div>
