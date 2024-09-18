---
title: Inside Look at Tom's Hardware Breakdowns and Comparisons
date: 2024-09-15T23:42:12.201Z
updated: 2024-09-17T17:31:23.008Z
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
<li><a href="https://fox-glue.techidaily.com/2024-approved-dji-drones-collection-entry-grade-premium-pro-elite-4k-flight/"><u>2024 Approved DJI Drones Collection Entry Grade, Premium Pro, Elite 4K Flight</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/breakthrough-announcement-intel-targets-cpu-stability-issues-with-upcoming-voltage-adjustment-patch-in-august/"><u>Breakthrough Announcement: Intel Targets CPU Stability Issues with Upcoming Voltage Adjustment Patch in August</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-come-up-with-the-best-pokemon-team-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>How to Come up With the Best Pokemon Team On Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-superior-global-stage-viewings/"><u>In 2024, Superior Global Stage Viewings</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/install-microsoft-ergo-keyboard-4000-drivers-hassle-free-step-by-step-instructions-included/"><u>Install Microsoft Ergo Keyboard 4000 Drivers Hassle-Free – Step by Step Instructions Included</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/johannes-honterus-a-great-personality-who-inspires-and-motivates-us/"><u>Johannes Honterus: A Great Personality Who Inspires And Motivates Us</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-2024-approved-pc-video-editors-similar-to-gopro-quik-top-picks/"><u>New 2024 Approved PC Video Editors Similar to GoPro Quik Top Picks</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-nokia-c02-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Nokia C02 FRP</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-quality-gigabyte-speaker-system-drivers-available-for-free-download/"><u>Top-Quality Gigabyte Speaker System Drivers Available for Free Download</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134493/18498" target="_top" id="2134493">
  <img src="//a.impactradius-go.com/display-ad/18498-2134493" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134493/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

