---
title: Inside Look at Tom's Hardware Breakdowns and Comparisons
date: 2024-09-26T17:57:41.293Z
updated: 2024-09-28T17:56:24.438Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/m73AaKbv4AF6cNcLYtefbX-320-80.jpg
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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-how-to-optimize-your-social-media-presence-post-facebook-change/"><u>[New] In 2024, How to Optimize Your Social Media Presence Post-Facebook Change</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-premium-podcast-partners-in-academia-for-2024/"><u>[New] Premium Podcast Partners in Academia for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-cutting-edge-design-top-5-3d-intro-makers/"><u>[Updated] 2024 Approved Cutting-Edge Design Top 5 3D Intro Makers</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-score-winning-tech-for-documenting-google-meets-freepaid/"><u>[Updated] In 2024, Score-Winning Tech for Documenting Google Meets (Free/Paid)</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-innovative-reclaim-review-the-ultimate-screen-recorder-for-2024/"><u>[Updated] Innovative 'Reclaim' Review – The Ultimate Screen Recorder for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-recording-conferences-on-a-budget-friendly-platform/"><u>2024 Approved Recording Conferences on a Budget-Friendly Platform</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/complete-tutorial-on-installing-and-refreshing-intel-hd-graphics-driver-v5500/"><u>Complete Tutorial on Installing & Refreshing Intel HD Graphics Driver V5500</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-the-magicard-rio-pro-driver-compatible-with-windows-10817-get-it-now/"><u>Download the Magicard Rio Pro Driver - Compatible with Windows 10/8.1/7: Get It Now!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-guide-installing-hps-840-g3-graphics-and-audio-drivers/"><u>Easy Guide: Installing HP's 840 G3 Graphics & Audio Drivers</u></a></li>
<li><a href="https://change-location.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-vivo-y55s-5g-2023-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Vivo Y55s 5G (2023)? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-samsung-galaxy-s23-tactical-edition-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Samsung Galaxy S23 Tactical Edition</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-nvidia-geforce-210-graphics-driver-updates-compatible-with-windows-11/"><u>Latest NVIDIA GeForce 210 Graphics Driver Updates Compatible with Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/optimize-system-storage-download-updated-intel-rapid-storage-technology-drivers-now/"><u>Optimize System Storage - Download Updated Intel Rapid Storage Technology Drivers Now!</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/unveiling-the-shortcomings-of-the-costly-microsoft-surface-duo-gadget/"><u>Unveiling the Shortcomings of the Costly Microsoft Surface Duo Gadget</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

