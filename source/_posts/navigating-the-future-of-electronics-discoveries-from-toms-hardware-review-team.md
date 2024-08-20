---
title: "Navigating the Future of Electronics: Discoveries From Tom's Hardware Review Team"
date: 2024-08-19T05:54:34.709Z
updated: 2024-08-20T05:54:34.709Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/66380fee6148181c7fbef919ab70be5b7f03dcd6ba9d00048b2c822f6ae741fb.jpg
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-crafting-gifs-from-youtube-detailed-step-by-step-guide-for-pcmobile/"><u>[New] 2024 Approved  Crafting GIFs From YouTube  Detailed Step-by-Step Guide for PC/Mobile</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-easy-steam-recordings-with-team-fortress-2s-latest-update/"><u>[New] In 2024, Easy Steam Recordings with Team Fortress 2'S Latest Update</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-stability-in-the-click-quashing-jitter/"><u>[New] Stability in the Click  Quashing Jitter</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-starry-secrets-a-guide-to-capturing-the-perfect-night-portraits-for-2024/"><u>[New] Starry Secrets  A Guide to Capturing the Perfect Night Portraits for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-steps-to-secure-clear-image-collections/"><u>[New] Steps to Secure, Clear Image Collections</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-accelerate-keyword-acquisition-the-finest-7-free-taggification-apps-for-youtube-videos/"><u>[Updated] 2024 Approved  Accelerate Keyword Acquisition  The Finest 7 Free Taggification Apps for YouTube Videos</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-best-ways-to-record-and-save-itunes-videos/"><u>[Updated] 2024 Approved  Best Ways to Record and Save iTunes Videos</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-optimized-strategies-for-youtube-and-facebook-cross-posting/"><u>[Updated] 2024 Approved  Optimized Strategies for YouTube & Facebook Cross-Posting</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/18083590-updated-streamline-your-thumbnail-design-journey-today/"><u>[Updated] Streamline Your Thumbnail Design Journey Today!</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-exclusive-list-top-sandbox-experiences/"><u>2024 Approved  Exclusive List  Top Sandbox Experiences</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722955975643-amd-radeon-rx-480-how-to-seamlessly-download-and-update-your-graphics-card-drivers/"><u>AMD Radeon RX 480 - How to Seamlessly Download & Update Your Graphics Card Drivers!</u></a></li>
<li><a href="https://article-helps.techidaily.com/beyond-basics-why-hdr-dominates-in-video-editing-workflows-for-2024/"><u>Beyond Basics  Why HDR Dominates in Video Editing Workflows for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/canon-mg3022-printers-find-your-official-drivers-and-get-the-newest-update-here/"><u>Canon MG3022 Printers: Find Your Official Drivers & Get the Newest Update Here</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/cutting-edge-tactics-for-engaging-social-media-medical-ads/"><u>Cutting-Edge Tactics for Engaging Social Media Medical Ads</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/dissecting-the-technology-behind-frapss-screenshot-pro-for-2024/"><u>Dissecting the Technology Behind Fraps's Screenshot Pro for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-install-amd-cryptocurrency-mining-software-on-windows/"><u>Download & Install AMD Cryptocurrency Mining Software on Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-install-canon-mx492mx-series-drivers-on-your-pc-step-by-step-instructions/"><u>Download & Install Canon MX492/Mx Series Drivers on Your PC: Step-by-Step Instructions</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-newest-gigabyte-nic-driver-to-optimize-your-internet-connection/"><u>Download the Newest Gigabyte NIC Driver to Optimize Your Internet Connection</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-honor-v-purse-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Honor V Purse Location Settings | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/enhancing-pc-performance-with-ease-the-definitive-guide-to-update-motherboard-drivers-in-windows/"><u>Enhancing PC Performance with Ease: The Definitive Guide to Update Motherboard Drivers in Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ensure-smooth-printer-functionality-hp-officejet-5255-drivers-update-and-download-steps/"><u>Ensure Smooth Printer Functionality: HP OfficeJet 5255 Drivers Update & Download Steps</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ensuring-seamless-connectivity-how-to-update-usb-drivers-on-samsung-mobile-devices/"><u>Ensuring Seamless Connectivity: How to Update USB Drivers on Samsung Mobile Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/essential-guide-to-selecting-a-best-fit-video-codec-in-windows/"><u>Essential Guide to Selecting a Best Fit Video Codec in Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/fast-and-hassle-free-installation-of-amd-ryzen-5-2400g-driver-updates/"><u>Fast and Hassle-Free Installation of AMD Ryzen 5 2400G Driver Updates</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722975334712-flawless-lenovo-thinkpad-driver-update-process-secure-download-options-here/"><u>Flawless Lenovo ThinkPad Driver Update Process - Secure Download Options Here!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/free-download-ultimate-guide-to-installing-focusrite-scarlett-solo-on-pc/"><u>Free Download: Ultimate Guide to Installing Focusrite Scarlett Solo on PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-nvidia-geforce-gtx-e-770-drivers-for-your-pc/"><u>Get the Latest NVIDIA GeForce GTX E 770 Drivers for Your PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-nvidia-geforce-gtx-1n60-super-driver-updates-installed/"><u>Get the Newest NVIDIA GeForce GTX 1N60 Super Driver Updates Installed</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-newest-updates-for-your-hp-deskjet-3700-driver-software-downloads-available-now/"><u>Get the Newest Updates for Your HP Deskjet 3700: Driver Software Downloads Available Now</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-free-zexmt-bluetooth-adapter-drivers-now-perfect-for-windows-7-8-and-1011-users/"><u>Get Your Free ZEXMT Bluetooth Adapter Drivers Now - Perfect For Windows 7, 8, and 10/11 Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-new-usb-c-driver-for-windows-1n-and-upgrade-today/"><u>Get Your New USB-C Driver for Windows 1N and Upgrade Today!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-i-sign-a-word-2021-free-by-ldigisigner-sign-a-word-sign-a-word/"><u>How do i sign a Word 2021 free</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-apple-iphone-xr-drfone-by-drfone-virtual-ios/"><u>How to Come up With the Best Pokemon Team On Apple iPhone XR? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-refresh-or-upgrade-ati-graphics-card-drivers-on-microsoft-windows-machines/"><u>How to Refresh or Upgrade ATI Graphics Card Drivers on Microsoft Windows Machines</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-fix-apple-id-verification-code-not-working-from-iphone-15-by-drfone-ios/"><u>In 2024, How To Fix Apple ID Verification Code Not Working From iPhone 15</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-logitech-g29-driving-controller-compatible-with-windows-10117/"><u>Install Logitech G29 Driving Controller Compatible with Windows 10/11/7</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-logitech-m185-drivers-complete-guide-and-download-links/"><u>Install Logitech M185 Drivers - Complete Guide & Download Links</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/optimizing-your-fb-profile-with-stunning-cover-videos-for-2024/"><u>Optimizing Your FB Profile with Stunning Cover Videos for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/pro-motherboard-drivers-easy-downloads-for-gamers/"><u>PRO Motherboard Drivers - Easy Downloads for Gamers</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-download-compatible-keyboard-software-for-windows-7-systems/"><u>Quick Download: Compatible Keyboard Software for Windows 7 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solve-the-dilemma-computer-unable-to-shut-down-under-windows-11-fixed/"><u>Solve the Dilemma: Computer Unable to Shut Down Under Windows 11 (FIXED)</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-to-downloading-the-right-canon-mg3620-drivers-securely/"><u>Step-by-Step Guide to Downloading the Right Canon MG3620 Drivers Securely</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-guide-updating-epson-xp-640-driver-for-windows-operating-system/"><u>Step-by-Step Guide: Updating Epson XP-640 Driver for Windows Operating System</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/step-by-step-updating-and-downloading-the-latest-intel-optane-drivers-for-your-pcs-efficiency/"><u>Step-by-Step: Updating and Downloading the Latest Intel Optane Drivers for Your PC's Efficiency</u></a></li>
<li><a href="https://techidaily.com/three-solutions-to-hard-reset-poco-m6-pro-4g-drfone-by-drfone-reset-android-reset-android/"><u>Three Solutions to Hard Reset Poco M6 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ultimate-tutorial-for-installing-latest-screen-graphics-drivers-on-windows/"><u>Ultimate Tutorial for Installing Latest Screen Graphics Drivers on Windows</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/update-to-the-newest-amd-rx-6700-xt-driver-for-all-microsoft-operating-systems/"><u>Update to the Newest AMD RX 6700 XT Driver for All Microsoft Operating Systems</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-creators-converge-and-craft-visual-stories-in-youtube-studio-for-2024/"><u>Where Creators Converge and Craft Visual Stories in Youtube Studio for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->