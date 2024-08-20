---
title: "Navigating the World of Computing: Insights From Tom's Hardware Hub"
date: 2024-08-19T05:52:47.499Z
updated: 2024-08-20T05:52:47.499Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/f780668281f43de469309d641324f16afda3a68eb738e8c283227d7e47f57830.jpg
---

## Legacy Over: How LLVM Compiler's Departure Signals the End of AMD's 3DNow

AMD’s near-ancient 3DNow! instructions have faded even further into obscurity.[Open-source compiler LLVM](https://github.com/llvm/llvm-project/commit/f0eb5587ceeb641445b64cb264c822b4751de04a) is finally removing support for the set of instructions that hasn’t been supported by AMD’s CPUs since 2011.

 The 3DNow! instruction set was introduced in 1998 as a competitor to Intel’s MMX. It added Single Instruction, Multiple Data (SIMD) instructions to AMD’s base x86 instruction set, which helped the CPUs do vector processing of floating-point operations using vector registers.

[AMD replaced 3DNow!](https://www.tomshardware.com/news/3dnow-simd-extensions-phenom-sse,11128.html) with the newer SSE equivalents in 2011 and stopped including that feature flag bit beginning with the K10 Bulldozer CPUs. It did take some time for compilers to start dropping support for the instruction set, though, since the CPUs remained in use for quite some time.

 In 2021,[Linux retired the instruction set](https://www.tomshardware.com/news/linux-says-goodbye-to-amd-3d-now) from its kernel, but LLVM maintained support long after everyone else dropped it. The developers behind the LLVM compiler also work to remove MMX types and instructions from the tool.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 A commit for LLVM 19, expected to be released in September or October, confirmed the impending removal.

 _“This set of instructions was only supported by AMD chips starting in the K6-2 (introduced 1998), and before the “Bulldozer” family (2011). They were never much used, as they were effectively superseded by the more-widely-implemented SSE (first implemented on the AMD side in Athlon XP in 2001)._

 _This is being done as a predecessor towards general removal of MMX register usage. Since there is almost no usage of the 3DNow! intrinsics, and no modern hardware even implements them, simple removal seems like the best option.”_

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 The AMD 3DNow! instructions were popular in the late 90s and early 2000s for improving gaming, video playback, and Adobe Photoshop workflows. Then, Intel released the SSE instructions, which became more dominant overall. When Intel released SSE2, AMD adopted it and dropped its older SIMD instruction set.

 Developers who need to write for old AMD processors can still use 3DNow! instructions in Assembly, including inline Assembly code with LLVM. Other than that, anything related to 3DNow! should be considered deprecated and no longer used.


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
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-viral-voyage-on-twitter-10-videos-igniting-widespread-interest/"><u>[New] 2024 Approved  Viral Voyage on Twitter  10 Videos Igniting Widespread Interest</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-leading-alternatives-to-twitter-ranked-best/"><u>[Updated] Leading Alternatives to Twitter, Ranked Best</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-midnight-tales-in-motion-evaluating-parental-choices-for-kids/"><u>2024 Approved  Midnight Tales in Motion  Evaluating Parental Choices for Kids</u></a></li>
<li><a href="https://discord-videos.techidaily.com/2024-approved-the-ultimate-strategy-for-role-assignment-on-discord/"><u>2024 Approved  The Ultimate Strategy for Role Assignment on Discord</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/bluetooth-usb-receiver-driver-download-from-techkey-supported-by-wndows-1078/"><u>Bluetooth USB Receiver Driver Download From Techkey - Supported by Wndows 10/7/8</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-jailbreaks-gone-silent-unveiling-7-reasons-why-theyre-no-longer-viable/"><u>ChatGPT Jailbreaks Gone Silent: Unveiling 7 Reasons Why They're No Longer Viable</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-guide-to-updating-and-downloading-atheros-drivers-on-windows/"><u>Complete Guide to Updating and Downloading Atheros Drivers on Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-guide-updating-the-drivers-of-your-epson-wf-n20-printer-wf-7620-on-a-windows-pc/"><u>Complete Guide: Updating the Drivers of Your Epson WF-N20 Printer (WF-7620) on a Windows PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-install-latest-firmware-netgear-wna3100/"><u>Download & Install Latest Firmware: Netgear WNA3100</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-drivers-for-xbox-360-controllers-compatible-software-and-installation-guide/"><u>Download Drivers for Xbox 360 Controllers: Compatible Software & Installation Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-official-canon-mg3620-drivers-easy-and-protected-steps-to-follow/"><u>Download the Official Canon MG3620 Drivers - Easy and Protected Steps to Follow</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-guide-to-downloading-and-installing-your-epson-stylus-nx420-printer-driver-on-windows/"><u>Easy Guide to Downloading and Installing Your Epson Stylus NX420 Printer Driver on Windows</u></a></li>
<li><a href="https://some-techniques.techidaily.com/expert-strategies-elevating-interview-audio-quality-with-iphoneipad-for-2024/"><u>Expert Strategies  Elevating Interview Audio Quality with iPhone/iPad for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-most-recent-amd-radeon-r5-graphics-driver-for-all-windows-versions-including-win-11-10-8-and-nw/"><u>Get the Most Recent AMD Radeon R5 Graphics Driver for All Windows Versions Including Win 11, 10, 8 & Nw</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-most-recent-wi-fi-drivers-compatible-with-windows-111087-download-now/"><u>Get the Most Recent Wi-Fi Drivers Compatible with Windows 11/10/8/7 – Download Now!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-asus-pce-ac68-driver-for-enhanced-connectivity-now-available/"><u>Get the Newest ASUS PCE-AC68 Driver for Enhanced Connectivity – Now Available</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-hp-color-laserjet-pro-m4n-dm-driver-installed-today/"><u>Get Your HP Color LaserJet Pro M4n-Dm Driver Installed Today</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-and-set-up-the-latest-steelseries-drivers-on-your-pc-with-windows-os/"><u>How to Get and Set Up the Latest SteelSeries Drivers on Your PC with Windows OS</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-update-or-install-hp-wifi-drivers-on-windows-computers-and-laptops/"><u>How to Update or Install HP Wifi Drivers on Windows Computers and Laptops</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722968591587-improve-your-pc-gaming-install-the-latest-geforce-rtx-2080-ti-drivers-today/"><u>Improve Your PC Gaming: Install the Latest GeForce RTX 2080 Ti Drivers Today</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-oppo-reno-11-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Oppo Reno 11 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-prime-list-cutting-through-the-noise-to-find-top-9-free-tools/"><u>In 2024, The Prime List  Cutting Through the Noise to Find Top 9 FREE Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-your-personal-igtv-channel-guide-for-inspiration/"><u>In 2024, Your Personal IGTV Channel Guide for Inspiration</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/installing-official-asus-driver-pack-for-optimal-hardware-performance-on-windows/"><u>Installing Official ASUS Driver Pack for Optimal Hardware Performance on Windows</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/investigating-the-rattling-audio-complaints-noctuas-response-for-its-new-nh-d15-g2-air-cooling-solution/"><u>Investigating the ‘Rattling’ Audio Complaints: Noctua's Response for Its New NH-D15 G2 Air Cooling Solution</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/new-release-lenovos-thunderbolt-3-usb-c-hub-driver-updates/"><u>New Release: Lenovo's Thunderbolt 3 USB-C Hub Driver Updates</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722967252203-revamp-your-samsung-smartphone-experience-update-the-usb-driver-today/"><u>Revamp Your Samsung Smartphone Experience - Update the USB Driver Today!</u></a></li>
<li><a href="https://media-tips.techidaily.com/simple-tricks-for-fast-high-quality-mp4-creation-from-iso-archives/"><u>Simple Tricks for Fast, High-Quality MP4 Creation From ISO Archives</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-to-downloading-and-using-steelseries-keyboards-engine-driver/"><u>Step-by-Step Guide to Downloading and Using SteelSeries Keyboard's Engine Driver</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-to-reinstalling-your-computers-usb-sound-card-drivers-for-windows-11/"><u>Step-by-Step Guide to Reinstalling Your Computer's USB Sound Card Drivers for Windows 11</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-xiaomi-13-ultra-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Xiaomi 13 Ultra ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722974782432-update-your-canon-d530s-camera-software-direct-download-instructions-here/"><u>Update Your Canon D530's Camera Software: Direct Download Instructions Here!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->