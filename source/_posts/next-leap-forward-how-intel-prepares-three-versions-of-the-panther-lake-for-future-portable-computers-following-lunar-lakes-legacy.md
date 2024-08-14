---
title: "Next Leap Forward: How Intel Prepares Three Versions of the Panther Lake for Future Portable Computers Following Lunar Lake's Legacy"
date: 2024-08-13T11:19:11.155Z
updated: 2024-08-14T11:19:11.155Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/28805214b423ac647ed00f851fe14b81181d6db73b669ce5e25a48073077851b.jpg
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

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-building-a-broad-spectrum-audience-with-multichannel-strategy/"><u>[New] 2024 Approved  Building a Broad-Spectrum Audience with Multichannel Strategy</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-effortless-gameplay-recordings-for-your-xbox-console/"><u>[New] 2024 Approved  Effortless Gameplay Recordings for Your Xbox Console</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-earhearer-live-sound-critique/"><u>[New] In 2024, EarHearer  Live Sound Critique</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-uncomplicated-techniques-reverse-playback-in-vlc-media-player/"><u>[New] In 2024, Uncomplicated Techniques  Reverse Playback in VLC Media Player</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-comprehensive-degree-of-view-analysis/"><u>[Updated] 2024 Approved  Comprehensive Degree of View Analysis</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-lose-yourself-to-laughter-best-10-jokes/"><u>[Updated] In 2024, Lose Yourself to Laughter  Best 10 Jokes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-pinnacle-choices-superior-mac-apps-for-grabbing-videos/"><u>[Updated] In 2024, Pinnacle Choices  Superior Mac Apps for Grabbing Videos</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-best-video-recording-gear-guide/"><u>2024 Approved  Best Video Recording Gear Guide</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-blur-a-picture-on-iphone-4-ways/"><u>2024 Approved  How to Blur a Picture on iPhone [4 Ways]</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/amd-graphics-card-drivers-update-guide-for-windows-10-11-and-7-operating-systems/"><u>AMD Graphics Card Drivers: Update Guide for Windows 10, 11, & 7 Operating Systems</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/approach-apply-knowledge-of-the-relationship-between-voltage-and-arc-blow-suscepteility/"><u>Approach: Apply Knowledge of the Relationship Between Voltage and Arc Blow Suscepteility.</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/canon-printer-drivers-for-mf8500c-on-windows-operating-systems-quick-download-guide/"><u>Canon Printer Drivers for MF8500C on Windows Operating Systems - Quick Download Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-guide-to-installing-updated-hp-officejet-pro-8610-printer-drivers-on-various-windows-versions/"><u>Complete Guide to Installing Updated HP Officejet Pro 8610 Printer Drivers on Various Windows Versions</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/direct-links-for-newest-nvidia-driver-updates-save-time-improve-performance/"><u>Direct Links for Newest NVIDIA Driver Updates - Save Time, Improve Performance</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-install-epson-gt-s50-driver-compatible-with-windows-os-versions-7-8-and-10/"><u>Download & Install Epson GT S50 Driver: Compatible with Windows OS Versions 7, 8 & 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-install-samsung-ssd-960-evo-drives-on-windows-pc-guide/"><u>Download & Install Samsung SSD 960 EVO Drives on Windows PC: Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-creative-x-fi-gamer-audio-driver-pack-for-windows-10/"><u>Download and Update Creative X-Fi Gamer Audio Driver Pack for Windows 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-essential-software-for-your-logitech-g-prodigy-gaming-mouse-g402/"><u>Download Essential Software for Your Logitech G Prodigy Gaming Mouse (G402)</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-new-intel-usb-30-driver-package-supporting-windows-11-systems/"><u>Download the New Intel USB 3.0 Driver Package Supporting Windows 11 Systems</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/dts-surround-sound-problem-solved-fixes-for-device-recognition-issues/"><u>DTS Surround Sound Problem Solved: Fixes for Device Recognition Issues</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-access-to-hps-professional-color-laser-jet-m452dn-printing-drivers/"><u>Easy Access to HP's Professional Color Laser Jet M452dn Printing Drivers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-installation-of-corsair-keyboards-on-pcs-using-windows-free-driver-download-available-now/"><u>Easy Installation of Corsair Keyboards on PCs Using Windows - Free Driver Download Available Now!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-installation-of-kyocera-printer-drivers-for-windows-users/"><u>Easy Installation of KYOCERA Printer Drivers for Windows Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-setup-guide-complete-your-behringer-audio-system-drivers-available-now/"><u>Easy Setup Guide: Complete Your Behringer Audio System - Drivers Available Now</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-update-guide-for-zebra-zp450-driver-software-download-and-installation-steps/"><u>Easy Update Guide for Zebra ZP450 Driver Software - Download & Installation Steps</u></a></li>
<li><a href="https://fox-access.techidaily.com/elevating-your-video-game-choosing-a-gimbal-for-drones/"><u>Elevating Your Video Game  Choosing a Gimbal for Drones</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/essential-update-hp-elitebook-x360-1030-g2-full-driver-pack-available-to-download/"><u>Essential Update: HP EliteBook X360 1030 G2 Full Driver Pack Available to Download</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/expert-advice-how-to-ensure-optimal-performance-by-refreshing-dell-xps-15-drivers-in-windows-environment/"><u>Expert Advice: How to Ensure Optimal Performance by Refreshing Dell XPS 15 Drivers in Windows Environment</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/expert-evaluation-of-the-pioneer-bdr-xs06-a-compact-powerful-blu-ray-disc-burning-solution/"><u>Expert Evaluation of the Pioneer BDR-XS06 - A Compact, Powerful Blu-Ray Disc Burning Solution</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/face-the-future-with-elite-iphone-and-android-modifiers-for-2024/"><u>Face the Future with Elite iPhone & Android Modifiers for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-canon-mp250-printer-drivers-latest-version-available/"><u>Free Canon MP250 Printer Drivers - Latest Version Available</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/freshest-rtx-2080-nvidia-graphics-card-driver-download-and-update-for-windows-1011-operating-system/"><u>Freshest RTX 2080 nVIDIA Graphics Card Driver Download & Update for Windows 10/11 Operating System</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-novice-to-master-the-ultimate-periscope-handbook/"><u>From Novice to Master  The Ultimate Periscope Handbook</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-fresh-updates-for-your-wacom-digital-drawing-board-download-latest-cintiq-13hd-driver-now/"><u>Get Fresh Updates for Your Wacom Digital Drawing Board: Download Latest Cintiq 13HD Driver Now</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-epson-gt-s50-printer-drivers-compatible-with-windows-7-8-and-10/"><u>Get the Latest Epson GT-S50 Printer Drivers Compatible with Windows 7, 8 & 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-drivers-for-intel-raid-and-matrix-storage-acceleration-on-windows-compatible-with-xp-through-to-windows-11/"><u>Get the Newest Drivers for Intel RAID & Matrix Storage Acceleration on Windows - Compatible with XP Through to Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-easily-update-your-amd-ryzen-drivers-step-by-step-instructions/"><u>How to Easily Update Your AMD Ryzen Drivers: Step-by-Step Instructions</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-newest-version-of-the-epson-xp-420-driver-step-by-step-guide/"><u>How To Get The Newest Version Of The Epson XP 420 Driver - Step By Step Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-install-the-best-asus-mousepad-driver-on-your-windows-device/"><u>How to Install the Best ASUS Mousepad Driver on Your Windows Device</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-install-the-newest-amd-rx-6800-graphics-driver-on-windows-operating-systems-111087/"><u>How to Install the Newest AMD RX 6800 Graphics Driver on Windows Operating Systems (11/10/8/7)</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-honor-x7b-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Honor X7b? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-securely-get-mouse-drivers-for-windows-7-operating-system/"><u>How To Securely Get Mouse Drivers For Windows 7 Operating System</u></a></li>
<li><a href="https://screen-recording.techidaily.com/in-2024-achieving-seamless-background-blurs-in-video-calls/"><u>In 2024, Achieving Seamless Background Blurs in Video Calls</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-are-reviews-on-goods-and-services-for-cash/"><u>In 2024, Are Reviews on Goods & Services for Cash?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-step-by-step-guide-to-applying-new-colors-and-textures-on-past-media/"><u>In 2024, Step-by-Step Guide to Applying New Colors & Textures on Past Media</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-lenovo-thinkpad-t420s-driver-updates-and-download-options-optimized-for-windows-11-users/"><u>Latest Lenovo ThinkPad T420s Driver Updates & Download Options Optimized for Windows 11 Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-logitech-g910-driver-installation-guide-for-windows-pcs/"><u>Latest Logitech G910 Driver Installation Guide for Windows PCs</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722977378260-maintains-a-uniform-temperature-gradient-for-better-heat-transfer-performance/"><u>Maintains a Uniform Temperature Gradient for Better Heat Transfer Performance</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/navigate-through-asus-pce-ac56-drivers-issues-on-windows-operating-systems-solutions-for-windows-11-8-and-7/"><u>Navigate Through ASUS PCE-AC56 Drivers Issues on Windows Operating Systems: Solutions for Windows 11, 8 & 7</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-mobile-video-editing-made-easy-best-free-special-effects-apps/"><u>New 2024 Approved Mobile Video Editing Made Easy Best Free Special Effects Apps</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-in-2024-creating-synchronized-media-incorporating-video-into-audio-streams/"><u>New In 2024, Creating Synchronized Media Incorporating Video Into Audio Streams</u></a></li>
<li><a href="https://extra-support.techidaily.com/quick-and-easy-steps-for-photos-in-your-instagram-gallery-for-2024/"><u>Quick and Easy Steps for Photos in Your Instagram Gallery for 2024</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/resolve-bad-configurations-fast-end-that-blue-screen-error-today/"><u>Resolve Bad Configurations Fast: End That Blue Screen Error Today</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/roccat-gaming-tech-mouse-driver-download-elevate-your-control-precision/"><u>Roccat Gaming Tech | Mouse Driver Download - Elevate Your Control Precision</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-finding-and-installing-lenovo-t430-drivers-for-multiple-windows-versions/"><u>Step-by-Step: Finding and Installing Lenovo T430 Drivers for Multiple Windows Versions</u></a></li>
<li><a href="https://network-issues.techidaily.com/steps-to-overcome-c1900101-installation-hiccup/"><u>Steps to Overcome C1900101 Installation Hiccup</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722889029297-tackling-troublesome-subwoofer-whirring-expert-fixes-revealed/"><u>Tackling Troublesome Subwoofer Whirring: Expert Fixes Revealed</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-oppo-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Oppo Phone</u></a></li>
<li><a href="https://fox-http.techidaily.com/unlock-the-secrets-maximizing-your-video-content-on-zoom-and-youtube-live-for-2024/"><u>Unlock the Secrets  Maximizing Your Video Content on Zoom & YouTube Live for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/update-to-the-latest-printing-driver-for-your-epson-wf-2650-on-windows-systems/"><u>Update to the Latest Printing Driver for Your Epson WF-2650 on Windows Systems</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/updating-your-amd-drivers-on-windows-10-11-and-7-a-comprehensive-guide/"><u>Updating Your AMD Drivers on Windows 10, 11 & 7: A Comprehensive Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722973071455-windows-7-intel-bluetooth-driver/"><u>Windows 7에서 Intel Bluetooth Driver를 쉽게 다운로드하는 루틴: 제가 도와주세요!</u></a></li>
</ul></div>
